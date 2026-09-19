<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvilx1q3c.css';
import '../../css/h/hmhhaybex.css';
import '../../css/a/a3gl68bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="kvilx1q3c"><path class="hmhhaybex"/><path class="a3gl68bbl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:phone-video-call" {...props}></Icon>
