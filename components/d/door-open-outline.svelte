<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tydr0ub5b.css';
import '../../css/j/jb41ocrxr.css';
import '../../css/k/ky0y4tb6r.css';
import '../../css/r/r-g9fqc8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="tydr0ub5b"/><path clip-rule="evenodd" class="jb41ocrxr"/><path class="ky0y4tb6r"/><path clip-rule="evenodd" class="r-g9fqc8x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:door-open-outline" {...props}></Icon>
