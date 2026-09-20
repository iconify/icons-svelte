<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p928398kq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p928398kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:die-face-with-six-pips" {...props}></Icon>
