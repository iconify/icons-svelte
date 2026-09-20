<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6ud6qgab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v6ud6qgab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coffin-with-nine-point-star-outline" {...props}></Icon>
