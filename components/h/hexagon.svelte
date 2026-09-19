<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8nzdvemh.css';
import '../../css/n/ndshnjb5c.css';
import '../../css/q/q3qds9b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="h8nzdvemh"><path class="ndshnjb5c"/><path class="q3qds9b_l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:hexagon" {...props}></Icon>
