<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u9b8kdn2z.css';
import '../../css/v/vpqn_7hdf.css';
import '../../css/l/lc-3a9m0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="u9b8kdn2z"/><path class="vpqn_7hdf"/><path class="lc-3a9m0i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:paint-brush-duo" {...props}></Icon>
