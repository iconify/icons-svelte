<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bpin_ybto.css';
import '../../css/z/z6u3wm4qg.css';
import '../../css/c/cmwyd1azu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="bpin_ybto"/><path clip-rule="evenodd" class="z6u3wm4qg"/><path class="cmwyd1azu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-west-bold" {...props}></Icon>
