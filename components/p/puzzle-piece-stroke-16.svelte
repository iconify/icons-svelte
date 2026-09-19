<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fakckpsqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fakckpsqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:puzzle-piece-stroke-16" {...props}></Icon>
