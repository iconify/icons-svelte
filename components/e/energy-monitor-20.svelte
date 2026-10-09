<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5nifvbes.css';
import '../../css/w/wewzkacif.css';
import '../../css/p/ptha_9bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z5nifvbes"/><path class="wewzkacif"/><path class="ptha_9bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-monitor-20" {...props}></Icon>
