<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jnd9-ne4y.css';
import '../../css/w/wfetx9b5h.css';
import '../../css/w/w4gnlobgl.css';
import '../../css/r/rwtx9qbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="jnd9-ne4y"/><path class="wfetx9b5h"/><path class="w4gnlobgl"/><path class="rwtx9qbrr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:flushed-face" {...props}></Icon>
