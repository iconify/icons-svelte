<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/z/zeb2u5bnn.css';
import '../../css/d/da5c6acvy.css';
import '../../css/r/rfi36zaxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="zeb2u5bnn"/><path class="da5c6acvy"/><path class="rfi36zaxv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:mall-bag" {...props}></Icon>
