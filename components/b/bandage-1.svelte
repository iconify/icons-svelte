<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h56op_7tl.css';
import '../../css/l/lhlp-obvy.css';
import '../../css/j/ja0wztbpr.css';
import '../../css/n/nmghvqs2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="h56op_7tl"/><path class="lhlp-obvy"/><path class="ja0wztbpr"/><path class="nmghvqs2p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:bandage-1" {...props}></Icon>
