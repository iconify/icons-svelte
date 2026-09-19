<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/u/utf5_xbzs.css';
import '../../css/o/okm2k4dpt.css';
import '../../css/e/ef5juj20y.css';
import '../../css/s/sl65mob2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="utf5_xbzs"/><path class="okm2k4dpt"/><path class="ef5juj20y"/><path clip-rule="evenodd" class="sl65mob2c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:adobe-indesign" {...props}></Icon>
