<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o5f05obqd.css';
import '../../css/i/idcl1o6gj.css';
import '../../css/i/i4_ls1u0b.css';
import '../../css/r/rkot81n8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="o5f05obqd"/><path class="idcl1o6gj"/><path class="i4_ls1u0b"/><path class="rkot81n8t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bell-duo" {...props}></Icon>
