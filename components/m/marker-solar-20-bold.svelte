<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hei8_htdz.css';
import '../../css/a/aopyufa5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hei8_htdz"/><path class="aopyufa5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:marker-solar-20-bold" {...props}></Icon>
