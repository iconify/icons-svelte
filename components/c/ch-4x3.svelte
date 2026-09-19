<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv9qcacyl.css';
import '../../css/l/lbq_y8bzz.css';
import '../../css/n/n1mjunbsu.css';
import '../../css/e/edsn48boz.css';
import '../../css/g/gzr-zob0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<g class="nv9qcacyl"><path class="lbq_y8bzz"/><g class="n1mjunbsu"><path class="edsn48boz"/><path class="gzr-zob0i"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ch-4x3" {...props}></Icon>
