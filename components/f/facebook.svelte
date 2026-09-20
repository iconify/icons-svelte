<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qesjik02s.css';
import '../../css/c/c5__zobli.css';
import '../../css/o/o1mzd_r6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666.667,"height":666.667};
const content = `<defs><clipPath id="SVGtqzMtbni" clipPathUnits="userSpaceOnUse"><path class="qesjik02s"/></clipPath></defs><g clip-path="url(#SVGtqzMtbni)" transform="matrix(1.33333 0 0 -1.33333 -133.333 800)"><path class="c5__zobli"/><path class="o1mzd_r6r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:facebook" {...props}></Icon>
