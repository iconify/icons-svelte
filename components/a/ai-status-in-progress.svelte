<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw3u8dcyu.css';
import '../../css/s/s3bjnib6t.css';
import '../../css/u/uyfynbbwi.css';
import '../../css/e/e5f-_gbbc.css';
import '../../css/b/bpmd7mglb.css';
import '../../css/d/d3uh6cy-d.css';
import '../../css/g/g-keuubov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rw3u8dcyu"/><path class="s3bjnib6t"/><path class="uyfynbbwi"/><path class="e5f-_gbbc"/><circle class="bpmd7mglb"/><circle class="d3uh6cy-d"/><circle class="g-keuubov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ai-status-in-progress" {...props}></Icon>
