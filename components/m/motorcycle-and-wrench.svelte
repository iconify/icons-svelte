<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruyn-vy-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ruyn-vy-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:motorcycle-and-wrench" {...props}></Icon>
