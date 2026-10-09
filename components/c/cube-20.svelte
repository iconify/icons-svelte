<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0t5o3l-d.css';
import '../../css/k/k4k55lxkj.css';
import '../../css/v/vl7jw2b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f0t5o3l-d"/><path class="k4k55lxkj"/><path class="vl7jw2b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cube-20" {...props}></Icon>
