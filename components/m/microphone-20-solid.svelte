<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i75exxbjl.css';
import '../../css/e/eu1d5q63v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="i75exxbjl"/><path class="eu1d5q63v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:microphone-20-solid" {...props}></Icon>
