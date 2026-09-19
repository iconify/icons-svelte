<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/a/a4y7rqb1n.css';
import '../../css/e/e6qicfbfp.css';
import '../../css/f/ftyot39ay.css';
import '../../css/k/kz0_pvboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="a4y7rqb1n"/><path class="e6qicfbfp"/><path class="ftyot39ay"/><path class="kz0_pvboy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:record-outline" {...props}></Icon>
