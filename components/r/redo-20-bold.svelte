<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8x0ib4bs.css';
import '../../css/v/vjnfcfbjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h8x0ib4bs"/><path class="vjnfcfbjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:redo-20-bold" {...props}></Icon>
