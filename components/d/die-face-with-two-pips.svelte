<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whbq-6bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="whbq-6bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:die-face-with-two-pips" {...props}></Icon>
