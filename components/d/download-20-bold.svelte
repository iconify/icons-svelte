<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm6fofg8e.css';
import '../../css/j/j9dw79bzp.css';
import '../../css/o/oypn0j-vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hm6fofg8e"/><path class="j9dw79bzp"/><path class="oypn0j-vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:download-20-bold" {...props}></Icon>
