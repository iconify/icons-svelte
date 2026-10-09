<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6jd9_b7p.css';
import '../../css/b/bvgd0jb0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j6jd9_b7p"/><path class="bvgd0jb0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crane-hook-20-bold" {...props}></Icon>
