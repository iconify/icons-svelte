<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/v/vmd8dr46i.css';
import '../../css/b/bx-7x9snt.css';
import '../../css/c/c6upwkbge.css';
import '../../css/h/h82j8jb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vmd8dr46i"/><path class="bx-7x9snt"/><path class="c6upwkbge"/><path class="h82j8jb4j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-bar-sparkles-sharp-two-tone" {...props}></Icon>
