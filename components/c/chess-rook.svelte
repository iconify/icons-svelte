<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1whq8ces.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="d1whq8ces"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:chess-rook" {...props}></Icon>
