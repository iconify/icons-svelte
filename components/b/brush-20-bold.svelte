<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvp9p07ws.css';
import '../../css/n/n3lls7b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rvp9p07ws"/><path class="n3lls7b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:brush-20-bold" {...props}></Icon>
