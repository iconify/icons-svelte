<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/y/y6f0jibvm.css';
import '../../css/m/mx8qzubgz.css';
import '../../css/e/eljct9bgn.css';
import '../../css/f/f4dapabmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="y6f0jibvm"/><path class="mx8qzubgz"/><path class="eljct9bgn"/><path class="f4dapabmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:round-socket" {...props}></Icon>
