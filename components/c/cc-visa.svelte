<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo-cg314a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1536};
const content = `<path class="oo-cg314a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:cc-visa" {...props}></Icon>
