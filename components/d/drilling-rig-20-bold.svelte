<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tly2nbbsq.css';
import '../../css/e/eoifswn5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tly2nbbsq"/><path class="eoifswn5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drilling-rig-20-bold" {...props}></Icon>
