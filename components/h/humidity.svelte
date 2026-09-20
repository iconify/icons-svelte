<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wzpei7bmr.css';
import '../../css/m/mmutxxbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<g class="cuyn6tgcc"><path class="wzpei7bmr"/><path class="mmutxxbyz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:humidity" {...props}></Icon>
