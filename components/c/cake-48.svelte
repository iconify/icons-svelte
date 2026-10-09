<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl5eyibfe.css';
import '../../css/y/y7rl90rrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nl5eyibfe"/><path class="y7rl90rrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cake-48" {...props}></Icon>
