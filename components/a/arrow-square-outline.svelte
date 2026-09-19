<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ijc771bml.css';
import '../../css/t/tjevbdcod.css';
import '../../css/v/vbu5lbs7n.css';
import '../../css/x/x8fnyzbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ijc771bml"/><path clip-rule="evenodd" class="tjevbdcod"/><path class="vbu5lbs7n"/><path clip-rule="evenodd" class="x8fnyzbyf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-square-outline" {...props}></Icon>
