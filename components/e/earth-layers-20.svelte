<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5l2hstxs.css';
import '../../css/y/yub7c6b0d.css';
import '../../css/g/g6wu-497r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q5l2hstxs"/><path class="yub7c6b0d"/><path class="g6wu-497r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:earth-layers-20" {...props}></Icon>
