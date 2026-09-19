<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i_7hthb3d.css';
import '../../css/i/iorsr0bkz.css';
import '../../css/s/sj_86q2hc.css';
import '../../css/d/dm9cfkb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="i_7hthb3d"/><path class="iorsr0bkz"/><circle class="sj_86q2hc"/><circle class="dm9cfkb6z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:category-management" {...props}></Icon>
