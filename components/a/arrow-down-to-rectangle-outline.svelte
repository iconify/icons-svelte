<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8akckbgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t8akckbgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-down-to-rectangle-outline" {...props}></Icon>
