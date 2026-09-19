<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/a/a0w1mqrvs.css';
import '../../css/o/ocg2edccm.css';
import '../../css/x/x4rdw3dgg.css';
import '../../css/g/gp03omb9u.css';
import '../../css/x/xu6ubfb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="a0w1mqrvs"/><path class="ocg2edccm"/><path class="x4rdw3dgg"/><path class="gp03omb9u"/><path class="xu6ubfb5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:delete-five" {...props}></Icon>
