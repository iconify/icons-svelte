<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/p/pbruvwbic.css';
import '../../css/b/b064tu1ws.css';
import '../../css/k/k4tp0gbvb.css';
import '../../css/s/sc_fqnbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="pbruvwbic"/><path class="b064tu1ws"/><circle class="k4tp0gbvb"/><path class="sc_fqnbin"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:pic-one" {...props}></Icon>
