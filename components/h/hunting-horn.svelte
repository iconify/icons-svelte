<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oln5j1o1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oln5j1o1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hunting-horn" {...props}></Icon>
