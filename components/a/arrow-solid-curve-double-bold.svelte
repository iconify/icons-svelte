<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/a/a1phhubdt.css';
import '../../css/r/roilbdb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":83};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="a1phhubdt"/><path class="roilbdb6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-solid-curve-double-bold" {...props}></Icon>
