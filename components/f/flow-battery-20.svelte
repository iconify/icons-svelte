<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2tojgbsp.css';
import '../../css/z/z8jy6p5aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n2tojgbsp"/><path class="z8jy6p5aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flow-battery-20" {...props}></Icon>
