<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fr8kns7oi.css';
import '../../css/r/r24ndllyp.css';
import '../../css/j/jr2950bfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="fr8kns7oi"/><path class="r24ndllyp"/><path class="jr2950bfp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:box-1-duo" {...props}></Icon>
