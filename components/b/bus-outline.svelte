<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/ygcr4ibxb.css';
import '../../css/q/qgieelblm.css';
import '../../css/y/yx4lsi7ye.css';
import '../../css/e/e-26mxbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ygcr4ibxb"/><path class="qgieelblm"/><path class="yx4lsi7ye"/><path class="e-26mxbxv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bus-outline" {...props}></Icon>
