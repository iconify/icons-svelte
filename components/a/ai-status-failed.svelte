<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw3u8dcyu.css';
import '../../css/s/s3bjnib6t.css';
import '../../css/u/uyfynbbwi.css';
import '../../css/v/vwg5vm92d.css';
import '../../css/t/tgv4tnkgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rw3u8dcyu"/><path class="s3bjnib6t"/><path class="uyfynbbwi"/><path class="vwg5vm92d"/><path class="tgv4tnkgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ai-status-failed" {...props}></Icon>
