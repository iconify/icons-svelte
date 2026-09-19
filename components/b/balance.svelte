<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsfne-b7l.css';
import '../../css/z/z-gksw3iv.css';
import '../../css/c/crl6_3vrk.css';
import '../../css/b/bru-ju65v.css';
import '../../css/s/s_-a9rbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nsfne-b7l"><path class="z-gksw3iv"/><path class="crl6_3vrk"/><path class="bru-ju65v"/><path class="s_-a9rbnb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:balance" {...props}></Icon>
