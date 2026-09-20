<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjy_hdcyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjy_hdcyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber-color:map-target-2" {...props}></Icon>
