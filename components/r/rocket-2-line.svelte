<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfq1-iboq.css';
import '../../css/x/x0ws1hdqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfq1-iboq"/><path class="x0ws1hdqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rocket-2-line" {...props}></Icon>
