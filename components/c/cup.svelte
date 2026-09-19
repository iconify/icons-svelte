<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/y/yw5nrdgml.css';
import '../../css/u/u8pcfmh1p.css';
import '../../css/r/rfia81eko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":49,"height":48};
const content = `<g class="hit3bi0-v"><path class="yw5nrdgml"/><path class="u8pcfmh1p"/><path class="rfia81eko"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:cup" {...props}></Icon>
