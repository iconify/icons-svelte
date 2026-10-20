<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq1625qbk.css';
import '../../css/v/v0h99ub0p.css';
import '../../css/q/qv75hb33y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vq1625qbk"/><path class="v0h99ub0p"/><path class="qv75hb33y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clock-alert-48-bold" {...props}></Icon>
