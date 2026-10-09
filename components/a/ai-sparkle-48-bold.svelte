<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3uo2ubmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z3uo2ubmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ai-sparkle-48-bold" {...props}></Icon>
