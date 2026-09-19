<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/q/q1oo2lbjw.css';
import '../../css/h/hi30kmb4w.css';
import '../../css/r/r67uvtzmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="q1oo2lbjw"/><path class="hi30kmb4w"/><path class="r67uvtzmv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:printer" {...props}></Icon>
