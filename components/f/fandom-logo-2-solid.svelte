<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooonye2mf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ooonye2mf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:fandom-logo-2-solid" {...props}></Icon>
