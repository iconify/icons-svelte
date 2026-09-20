<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_csi6bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_csi6bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:natural-gas-outline" {...props}></Icon>
