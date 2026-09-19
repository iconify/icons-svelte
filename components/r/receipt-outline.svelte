<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kcu1bjbdy.css';
import '../../css/m/mcqy7wbbq.css';
import '../../css/c/c9hgkzb7l.css';
import '../../css/q/qlowtstmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="kcu1bjbdy"/><path clip-rule="evenodd" class="mcqy7wbbq"/><path class="c9hgkzb7l"/><path clip-rule="evenodd" class="qlowtstmq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:receipt-outline" {...props}></Icon>
