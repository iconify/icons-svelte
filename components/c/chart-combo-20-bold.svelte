<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8r44id8f.css';
import '../../css/h/h75qckbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u8r44id8f"/><path class="h75qckbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-combo-20-bold" {...props}></Icon>
