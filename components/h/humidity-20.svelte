<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8cq105ge.css';
import '../../css/r/r7j0j19px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j8cq105ge"/><path class="r7j0j19px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:humidity-20" {...props}></Icon>
