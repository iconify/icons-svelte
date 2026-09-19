<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/om4qpc7yf.css';
import '../../css/f/fic12db1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="om4qpc7yf"/><path class="fic12db1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:happy" {...props}></Icon>
