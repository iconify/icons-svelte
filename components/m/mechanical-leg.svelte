<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cf6cc58cf.css';
import '../../css/e/e1-g6mxfo.css';
import '../../css/f/fs2x14b2h.css';
import '../../css/y/yv22s9oyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="cf6cc58cf"/><path class="e1-g6mxfo"/><path class="fs2x14b2h"/><path class="yv22s9oyq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:mechanical-leg" {...props}></Icon>
