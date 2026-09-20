<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se2jd0tlq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="se2jd0tlq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:heart-outline-with-left-half-and-bottom-right-quarter" {...props}></Icon>
