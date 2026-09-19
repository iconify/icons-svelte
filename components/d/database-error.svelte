<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/q/q0egn3lpb.css';
import '../../css/g/g2n1prb3y.css';
import '../../css/g/gecs6xp5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<g transform="translate(2)" class="n1lsf0bnc"><ellipse class="q0egn3lpb"/><path class="g2n1prb3y"/><path class="gecs6xp5p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:database-error" {...props}></Icon>
