<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6zkfm9wf.css';
import '../../css/u/uuc-d5buj.css';
import '../../css/i/iw_-l-b0y.css';
import '../../css/r/rj8pwo61t.css';
import '../../css/h/hq6hy3pct.css';
import '../../css/a/az_x4yp1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z6zkfm9wf"/><path class="uuc-d5buj"/><path class="iw_-l-b0y"/><path class="rj8pwo61t"/><path class="hq6hy3pct"/><path class="az_x4yp1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bicycle-20" {...props}></Icon>
