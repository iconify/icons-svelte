<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmk6nb6wm.css';
import '../../css/c/c-wb1qbgr.css';
import '../../css/e/egbtnbclf.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="bmk6nb6wm clr-i-outline--alerted clr-i-outline-path-1--alerted"/><path class="c-wb1qbgr clr-i-outline--alerted clr-i-outline-path-2--alerted"/><path class="clr-i-alert clr-i-outline--alerted clr-i-outline-path-3--alerted egbtnbclf"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:curve-chart-outline-alerted" {...props}></Icon>
