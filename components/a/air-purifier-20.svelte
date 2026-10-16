<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf306wb4g.css';
import '../../css/q/q0wunibak.css';
import '../../css/e/e3e6rzbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qf306wb4g"/><path class="q0wunibak"/><path class="e3e6rzbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:air-purifier-20" {...props}></Icon>
