<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndxv2tm2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ndxv2tm2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:elastic-x-pack-logo-solid" {...props}></Icon>
