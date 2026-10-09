<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvdnlfa5d.css';
import '../../css/r/r4-rvcapq.css';
import '../../css/m/mw_9bdu9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uvdnlfa5d"/><path class="r4-rvcapq"/><path class="mw_9bdu9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:box-48-bold" {...props}></Icon>
