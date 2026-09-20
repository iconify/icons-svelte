<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn6yq3b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rn6yq3b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:r-light" {...props}></Icon>
