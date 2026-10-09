<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9yioib4q.css';
import '../../css/f/ffopgc0dq.css';
import '../../css/p/pe6rmrbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z9yioib4q"/><path class="ffopgc0dq"/><path class="pe6rmrbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-van-48" {...props}></Icon>
