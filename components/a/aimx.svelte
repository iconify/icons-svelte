<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmt424bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmt424bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:aimx" {...props}></Icon>
