<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1de22b7f.css';
import '../../css/w/wzwobcbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i1de22b7f"/><path class="wzwobcbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pickaxe-20-bold" {...props}></Icon>
