<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opt71mb5e.css';
import '../../css/k/k1vorjqdj.css';
import '../../css/r/rg1xqfbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="opt71mb5e"/><path class="k1vorjqdj"/><path class="rg1xqfbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gavel-48" {...props}></Icon>
