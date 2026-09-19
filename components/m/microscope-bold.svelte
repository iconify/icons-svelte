<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/owgq43b1u.css';
import '../../css/l/lmb9nrbxa.css';
import '../../css/g/gwkwatchw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="owgq43b1u"/><path clip-rule="evenodd" class="lmb9nrbxa"/><path class="gwkwatchw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:microscope-bold" {...props}></Icon>
