<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u_cglrb8o.css';
import '../../css/z/ztzwvfbwf.css';
import '../../css/s/sfkx2xqaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="u_cglrb8o"/><path class="ztzwvfbwf"/><path class="sfkx2xqaz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:eye-slash" {...props}></Icon>
