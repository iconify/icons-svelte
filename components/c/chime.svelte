<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b8jnhibmg.css';
import '../../css/j/jac66gbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":193,"height":193,"left":-203,"top":444};
const content = `<g class="cuyn6tgcc"><path class="b8jnhibmg"/><path class="jac66gbbw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:chime" {...props}></Icon>
