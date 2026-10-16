<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_xy3blpc.css';
import '../../css/l/lewmoqbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t_xy3blpc"/><path class="lewmoqbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-pie-slice-20" {...props}></Icon>
