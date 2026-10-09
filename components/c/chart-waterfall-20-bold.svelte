<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8r44id8f.css';
import '../../css/n/n-7_zw30i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u8r44id8f"/><path class="n-7_zw30i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-waterfall-20-bold" {...props}></Icon>
