<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1fw4u24k.css';
import '../../css/a/ayk1lqtqi.css';
import '../../css/q/qbjntbton.css';
import '../../css/u/uzx1cpbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x1fw4u24k"/><path class="ayk1lqtqi"/><path class="qbjntbton"/><path class="uzx1cpbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drill-press-48" {...props}></Icon>
