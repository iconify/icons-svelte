<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tvp0f-b9t.css';
import '../../css/e/e5v1wybfk.css';
import '../../css/o/o1eh7fb7f.css';
import '../../css/q/qr1jw7bwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="tvp0f-b9t"/><path class="e5v1wybfk"/><path class="o1eh7fb7f"/><path class="qr1jw7bwa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:alarm-exclamation-duo" {...props}></Icon>
