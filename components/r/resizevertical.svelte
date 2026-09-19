<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2iyb1b_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":641,"height":1024};
const content = `<path class="c2iyb1b_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:resizevertical" {...props}></Icon>
