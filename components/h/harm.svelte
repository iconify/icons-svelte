<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/z/z2z8s690m.css';
import '../../css/d/dlenz_bwo.css';
import '../../css/s/stb41lb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="z2z8s690m"/><path class="dlenz_bwo"/><path class="stb41lb3k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:harm" {...props}></Icon>
