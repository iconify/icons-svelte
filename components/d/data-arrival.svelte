<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/f/fdlsegbxw.css';
import '../../css/q/qxakhabnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path clip-rule="evenodd" class="fdlsegbxw"/><path class="qxakhabnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:data-arrival" {...props}></Icon>
