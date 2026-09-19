<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/r/rw2u32bub.css';
import '../../css/b/bbty7xbeh.css';
import '../../css/n/n-ck6kb3l.css';
import '../../css/c/cwj85ccsx.css';
import '../../css/t/tiqbonweu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="rw2u32bub"/><path class="bbty7xbeh"/><path class="n-ck6kb3l"/><path class="cwj85ccsx"/><path class="tiqbonweu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:flashlight" {...props}></Icon>
