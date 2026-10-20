<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnovs-bfk.css';
import '../../css/o/ow9eo7bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bnovs-bfk"/><path class="ow9eo7bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lightbulb-sparkle-20" {...props}></Icon>
