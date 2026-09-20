<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr0pwhdae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dr0pwhdae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:oregon-with-capital-star" {...props}></Icon>
