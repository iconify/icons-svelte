<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x07oq7k1t.css';
import '../../css/h/h02a5vbhw.css';
import '../../css/b/bz2g1kbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x07oq7k1t"/><path class="h02a5vbhw"/><path class="bz2g1kbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bookmark-plus-20-bold" {...props}></Icon>
