<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6zkfm9wf.css';
import '../../css/r/rzyvrkbci.css';
import '../../css/n/no05bkayi.css';
import '../../css/r/rj8pwo61t.css';
import '../../css/h/hq6hy3pct.css';
import '../../css/j/j3n2_bb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z6zkfm9wf"/><path class="rzyvrkbci"/><path class="no05bkayi"/><path class="rj8pwo61t"/><path class="hq6hy3pct"/><path class="j3n2_bb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:e-bike-charging-20" {...props}></Icon>
