<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/h/hvve69bkn.css';
import '../../css/l/l88i7dblt.css';
import '../../css/t/tzpiabczw.css';
import '../../css/t/tw29b1vdl.css';
import '../../css/o/o594j2bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="hvve69bkn"/><path class="l88i7dblt"/><path class="tzpiabczw"/><path class="tw29b1vdl"/><path class="o594j2bhc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:expand-down" {...props}></Icon>
