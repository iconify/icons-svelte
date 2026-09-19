<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4y3p3btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="j4y3p3btl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:llvm" {...props}></Icon>
