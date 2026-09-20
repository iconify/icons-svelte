<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/e/e35pomtwe.css';
import '../../css/v/vd6q9kbib.css';
import '../../css/m/mrj31bc2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e35pomtwe"/><path class="vd6q9kbib"/><path class="mrj31bc2g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:filter-tick" {...props}></Icon>
