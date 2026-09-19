<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aq5kvfbtr.css';
import '../../css/w/wcspu5b7n.css';
import '../../css/u/uz70hsbcy.css';
import '../../css/o/ofxeqkbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="aq5kvfbtr"/><path class="wcspu5b7n"/><path class="uz70hsbcy"/><path class="ofxeqkbsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:coin-duo" {...props}></Icon>
