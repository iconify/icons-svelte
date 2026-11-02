<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxcpg12gh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxcpg12gh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:coathanger-fill" {...props}></Icon>
