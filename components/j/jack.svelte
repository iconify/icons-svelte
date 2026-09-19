<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/ddsnpbctj.css';
import '../../css/i/iosy5ibnu.css';
import '../../css/z/z2nswx2uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ddsnpbctj"/><path clip-rule="evenodd" class="iosy5ibnu"/><path class="z2nswx2uv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:jack" {...props}></Icon>
