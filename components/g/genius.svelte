<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nk4syz2ss.css';
import '../../css/u/u9wri7bhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":32};
const content = `<g class="cuyn6tgcc"><path class="nk4syz2ss"/><path class="u9wri7bhi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:genius" {...props}></Icon>
