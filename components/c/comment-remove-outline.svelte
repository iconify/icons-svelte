<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xzf26vbro.css';
import '../../css/x/xm929l28t.css';
import '../../css/t/tj416dxhv.css';
import '../../css/i/i5iq5xaql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="xzf26vbro"/><path clip-rule="evenodd" class="xm929l28t"/><path class="tj416dxhv"/><path clip-rule="evenodd" class="i5iq5xaql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:comment-remove-outline" {...props}></Icon>
