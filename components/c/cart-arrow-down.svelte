<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8tbz_byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="e8tbz_byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:cart-arrow-down" {...props}></Icon>
