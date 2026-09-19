<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abw90sbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="abw90sbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:cmake" {...props}></Icon>
