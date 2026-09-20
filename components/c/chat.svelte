<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/e/esykvidxt.css';
import '../../css/i/ib5oyob7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="nrj6p8qat"><path class="esykvidxt"/><path class="ib5oyob7o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:chat" {...props}></Icon>
