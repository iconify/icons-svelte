<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trdnv0bir.css';
import '../../css/e/el1y2bj9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="trdnv0bir"/><path class="el1y2bj9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bus-20-bold" {...props}></Icon>
