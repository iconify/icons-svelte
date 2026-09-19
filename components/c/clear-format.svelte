<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/v/vhoslxfon.css';
import '../../css/s/sul83f9ve.css';
import '../../css/o/obbrti2nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="h01tyzbfu"><path class="vhoslxfon"/><path class="sul83f9ve"/><path class="obbrti2nr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:clear-format" {...props}></Icon>
