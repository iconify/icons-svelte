<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lj43ppoag.css';
import '../../css/y/ymqifpb2e.css';
import '../../css/h/hr9jw4qtz.css';
import '../../css/z/z7pd3exzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lj43ppoag"/><path class="ymqifpb2e"/><path class="hr9jw4qtz"/><path class="z7pd3exzs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:note-sticky-duo" {...props}></Icon>
