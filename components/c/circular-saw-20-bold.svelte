<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot0mghbfc.css';
import '../../css/j/jwxwoobeu.css';
import '../../css/e/etrl1rckl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ot0mghbfc"/><path class="jwxwoobeu"/><path class="etrl1rckl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:circular-saw-20-bold" {...props}></Icon>
