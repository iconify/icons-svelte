<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veb-t1e3e.css';
import '../../css/r/rlbc0qbau.css';
import '../../css/q/qhozfjjix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="veb-t1e3e"/><path class="rlbc0qbau"/><path class="qhozfjjix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-flow-20-bold" {...props}></Icon>
