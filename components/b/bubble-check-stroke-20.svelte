<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esw9xfprr.css';
import '../../css/v/vo4v1ibev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="esw9xfprr"/><path class="vo4v1ibev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bubble-check-stroke-20" {...props}></Icon>
