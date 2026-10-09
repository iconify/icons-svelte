<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctmyokx8x.css';
import '../../css/j/j_as-15we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ctmyokx8x"/><path class="j_as-15we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nuclear-plant-20-bold" {...props}></Icon>
