<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ece_obukg.css';
import '../../css/d/d-c_9e2ou.css';
import '../../css/x/x3lv_0s-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ece_obukg"/><path class="d-c_9e2ou"/><path class="x3lv_0s-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:moneywithwings" {...props}></Icon>
