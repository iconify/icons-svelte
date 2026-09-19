<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rknc7jbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rknc7jbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:grid-3x3-gap" {...props}></Icon>
