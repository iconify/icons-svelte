<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf7x3vv8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vf7x3vv8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:hexagon-half" {...props}></Icon>
