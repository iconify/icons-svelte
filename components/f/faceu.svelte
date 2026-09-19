<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g9usotbod.css';
import '../../css/u/uv-ggnbgb.css';
import '../../css/o/oe3u2eq0u.css';
import '../../css/a/aw231xbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="g9usotbod"/><path class="uv-ggnbgb"/><ellipse class="oe3u2eq0u"/><ellipse class="aw231xbym"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:faceu" {...props}></Icon>
