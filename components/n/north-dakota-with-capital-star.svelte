<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyx2mnb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dyx2mnb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:north-dakota-with-capital-star" {...props}></Icon>
