<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws7p95bcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ws7p95bcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:caret-right-20-bold" {...props}></Icon>
