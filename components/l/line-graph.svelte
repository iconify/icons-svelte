<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j90egs33e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j90egs33e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:line-graph" {...props}></Icon>
