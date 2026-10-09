<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7588rxqu.css';
import '../../css/w/w97g-pbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j7588rxqu"/><path class="w97g-pbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:microgrid-20-bold" {...props}></Icon>
