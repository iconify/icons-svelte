<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/e/ezq3zxkis.css';
import '../../css/y/y0dlarb3n.css';
import '../../css/m/mv7_v6hps.css';
import '../../css/q/q8f8vcygc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ezq3zxkis"/><path clip-rule="evenodd" class="y0dlarb3n"/><path class="mv7_v6hps"/><path class="q8f8vcygc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:microscope" {...props}></Icon>
