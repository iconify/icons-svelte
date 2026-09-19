<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu-vsqb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zu-vsqb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:chess-queen" {...props}></Icon>
