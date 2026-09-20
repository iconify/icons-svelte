<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1wohmrfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h1wohmrfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-wheel-with-tire" {...props}></Icon>
