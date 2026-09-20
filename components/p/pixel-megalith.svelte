<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rorr57bgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rorr57bgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-megalith" {...props}></Icon>
