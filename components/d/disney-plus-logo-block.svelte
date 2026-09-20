<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8u5iic6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m8u5iic6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:disney-plus-logo-block" {...props}></Icon>
