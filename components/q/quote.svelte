<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xel_qjvvf.css';
import '../../css/d/dxpqquqan.css';
import '../../css/v/vw1njlwto.css';
import '../../css/b/bpbf5viwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="xel_qjvvf"/><path class="dxpqquqan"/><path clip-rule="evenodd" class="vw1njlwto"/><path class="bpbf5viwi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:quote" {...props}></Icon>
