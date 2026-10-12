<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-khqclun.css';
import '../../css/e/e6u7bf88s.css';
import '../../css/f/f020qv8gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z-khqclun"/><path class="e6u7bf88s"/><path class="f020qv8gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cnc-machine-20" {...props}></Icon>
