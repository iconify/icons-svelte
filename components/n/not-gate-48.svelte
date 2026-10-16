<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcke4yb4t.css';
import '../../css/g/gdu4k7b7m.css';
import '../../css/l/lppnqit-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vcke4yb4t"/><path class="gdu4k7b7m"/><path class="lppnqit-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:not-gate-48" {...props}></Icon>
