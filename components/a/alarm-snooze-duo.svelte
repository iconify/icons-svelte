<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tvp0f-b9t.css';
import '../../css/e/e5v1wybfk.css';
import '../../css/q/qisn-co-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="tvp0f-b9t"/><path class="e5v1wybfk"/><path class="qisn-co-d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:alarm-snooze-duo" {...props}></Icon>
