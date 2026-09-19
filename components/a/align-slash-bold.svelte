<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/af0f5krwx.css';
import '../../css/x/xwbtsryeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":81};
const content = `<g class="ft5dv1b6b"><path class="af0f5krwx"/><path class="xwbtsryeu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:align-slash-bold" {...props}></Icon>
