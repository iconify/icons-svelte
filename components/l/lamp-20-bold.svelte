<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhbboj22q.css';
import '../../css/a/a8ccsebhs.css';
import '../../css/m/mivqt5bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xhbboj22q"/><path class="a8ccsebhs"/><path class="mivqt5bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lamp-20-bold" {...props}></Icon>
