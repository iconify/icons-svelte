<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q1g5s_bga.css';
import '../../css/s/sosv7zf-y.css';
import '../../css/p/pk2ijs5sj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="q1g5s_bga"/><path class="sosv7zf-y"/><path class="pk2ijs5sj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:inbox-duo" {...props}></Icon>
