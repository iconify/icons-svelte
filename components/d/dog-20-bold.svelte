<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyee1r7bl.css';
import '../../css/r/rvcii1b1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zyee1r7bl"/><path class="rvcii1b1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dog-20-bold" {...props}></Icon>
