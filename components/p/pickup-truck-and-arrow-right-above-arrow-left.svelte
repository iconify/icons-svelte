<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji2s539xn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ji2s539xn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pickup-truck-and-arrow-right-above-arrow-left" {...props}></Icon>
