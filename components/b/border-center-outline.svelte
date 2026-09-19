<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j07ug2b2j.css';
import '../../css/b/be78hac3b.css';
import '../../css/q/q_8ldsbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="j07ug2b2j"/><path class="be78hac3b"/><path clip-rule="evenodd" class="q_8ldsbpo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:border-center-outline" {...props}></Icon>
