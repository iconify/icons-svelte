<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ixa9i89oh.css';
import '../../css/m/mj6mvfbak.css';
import '../../css/f/f1lq2jbwk.css';
import '../../css/q/q2lp95bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ixa9i89oh"/><path class="mj6mvfbak"/><path class="f1lq2jbwk"/><path class="q2lp95bup"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:farm-duo" {...props}></Icon>
