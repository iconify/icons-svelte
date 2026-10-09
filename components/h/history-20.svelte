<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thr7ovb8q.css';
import '../../css/o/ogpkn9bgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="thr7ovb8q"/><path class="ogpkn9bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:history-20" {...props}></Icon>
