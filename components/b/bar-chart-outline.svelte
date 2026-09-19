<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou5lp3-8i.css';
import '../../css/f/fcfjhdcnf.css';
import '../../css/e/e7n2iruil.css';
import '../../css/q/qaayn7bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ou5lp3-8i"/><rect class="fcfjhdcnf"/><rect class="e7n2iruil"/><rect class="qaayn7bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bar-chart-outline" {...props}></Icon>
