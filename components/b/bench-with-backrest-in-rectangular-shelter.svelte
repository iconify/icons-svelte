<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3-u2ubdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f3-u2ubdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bench-with-backrest-in-rectangular-shelter" {...props}></Icon>
