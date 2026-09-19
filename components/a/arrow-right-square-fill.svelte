<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/numz40fvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="numz40fvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-right-square-fill" {...props}></Icon>
