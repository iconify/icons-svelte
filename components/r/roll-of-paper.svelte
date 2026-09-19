<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/ky9ep5ygo.css';
import '../../css/q/q8dg84_vw.css';
import '../../css/q/qpvumgbpy.css';
import '../../css/l/lbhwhxbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ky9ep5ygo"/><path class="q8dg84_vw"/><path class="qpvumgbpy"/><path class="lbhwhxbsh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:roll-of-paper" {...props}></Icon>
