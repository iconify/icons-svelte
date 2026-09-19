<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nd__e9bwe.css';
import '../../css/x/xukwvbc4u.css';
import '../../css/j/j2dz8xbde.css';
import '../../css/r/rcrg8_0kv.css';
import '../../css/r/ryfi9jbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="nd__e9bwe"/><circle class="xukwvbc4u"/><circle class="j2dz8xbde"/><circle class="rcrg8_0kv"/><circle class="ryfi9jbiy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:frog" {...props}></Icon>
