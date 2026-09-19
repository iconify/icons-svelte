<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/x/xpua17bdp.css';
import '../../css/y/y3tc9-bzh.css';
import '../../css/t/tv_gun5-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><rect class="xpua17bdp"/><path class="y3tc9-bzh"/><path class="tv_gun5-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:horizontally-centered" {...props}></Icon>
