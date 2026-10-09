<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di7upcblc.css';
import '../../css/o/o5gtl8zhh.css';
import '../../css/w/we-nd7j-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="di7upcblc"/><path class="o5gtl8zhh"/><path class="we-nd7j-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:import-export-48" {...props}></Icon>
