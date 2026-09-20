<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x__7wzbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x__7wzbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:roman-numeral-ii-over-water" {...props}></Icon>
