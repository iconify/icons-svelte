<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dhpf8pbqq.css';
import '../../css/g/gdryfccos.css';
import '../../css/o/oxtw1expr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="dhpf8pbqq"/><path clip-rule="evenodd" class="gdryfccos"/><path class="oxtw1expr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:eyeglasses" {...props}></Icon>
