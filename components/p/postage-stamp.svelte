<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d99w1wg2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d99w1wg2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:postage-stamp" {...props}></Icon>
