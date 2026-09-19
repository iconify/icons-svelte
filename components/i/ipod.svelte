<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/rmp5hgbqp.css';
import '../../css/d/dfbuaacdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<g transform="translate(4)" class="n1lsf0bnc"><ellipse class="rmp5hgbqp"/><path class="dfbuaacdd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:ipod" {...props}></Icon>
