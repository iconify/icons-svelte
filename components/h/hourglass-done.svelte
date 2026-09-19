<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fej6-wblt.css';
import '../../css/f/fk97eubrf.css';
import '../../css/o/oiuah7msq.css';
import '../../css/z/z7jnd8bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="fej6-wblt"/><path class="fk97eubrf"/><path class="oiuah7msq"/><path class="z7jnd8bsx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:hourglass-done" {...props}></Icon>
