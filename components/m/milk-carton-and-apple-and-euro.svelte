<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5b2ksb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n5b2ksb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:milk-carton-and-apple-and-euro" {...props}></Icon>
