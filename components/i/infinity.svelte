<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6mizdc5u.css';
import '../../css/r/r8ikbo9ae.css';
import '../../css/o/o4dmadb3b.css';
import '../../css/o/o_kit7b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="v6mizdc5u"/><g class="r8ikbo9ae"><path class="o4dmadb3b"/><path class="o_kit7b-o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:infinity" {...props}></Icon>
