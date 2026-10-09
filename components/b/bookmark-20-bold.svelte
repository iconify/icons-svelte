<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x07oq7k1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x07oq7k1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bookmark-20-bold" {...props}></Icon>
