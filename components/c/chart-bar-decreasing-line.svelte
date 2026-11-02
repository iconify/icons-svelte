<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdaw-weoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdaw-weoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-bar-decreasing-line" {...props}></Icon>
