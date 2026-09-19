<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lovg5vbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lovg5vbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:bevyengine" {...props}></Icon>
