<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6215pfzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c6215pfzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:milk-carton-and-cheese" {...props}></Icon>
