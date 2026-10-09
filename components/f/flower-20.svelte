<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jixfx1hdh.css';
import '../../css/r/ra1vsdwoa.css';
import '../../css/e/ep6j9gigt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jixfx1hdh"/><path class="ra1vsdwoa"/><path class="ep6j9gigt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flower-20" {...props}></Icon>
