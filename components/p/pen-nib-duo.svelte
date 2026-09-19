<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qgm9wdbgk.css';
import '../../css/z/zne832bro.css';
import '../../css/a/argowfbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="qgm9wdbgk"/><path class="zne832bro"/><path class="argowfbtr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pen-nib-duo" {...props}></Icon>
