<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h14emmvzq.css';
import '../../css/c/cix91lbno.css';
import '../../css/d/deryr5bon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="h14emmvzq"/><rect class="cix91lbno"/><rect class="deryr5bon"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:die-2" {...props}></Icon>
