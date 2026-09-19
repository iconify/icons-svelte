<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dce5w2b3k.css';
import '../../css/r/rj0_dwbpf.css';
import '../../css/f/f4dci94xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="dce5w2b3k"/><path class="rj0_dwbpf"/><path class="f4dci94xs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-solid-line-start-bold" {...props}></Icon>
