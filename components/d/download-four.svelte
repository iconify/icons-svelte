<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/m/mtr8gtysq.css';
import '../../css/x/x9_-dnb2u.css';
import '../../css/x/xg20wgnod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path clip-rule="evenodd" class="mtr8gtysq"/><path class="x9_-dnb2u"/><path class="xg20wgnod"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:download-four" {...props}></Icon>
