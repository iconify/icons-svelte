<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr079etta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dr079etta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:lock" {...props}></Icon>
