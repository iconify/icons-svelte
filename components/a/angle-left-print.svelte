<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oth0a1bfn.css';
import '../../css/t/t-a9dubga.css';
import '../../css/a/a98oukb7r.css';
import '../../css/z/zf8ge10as.css';
import '../../css/z/z2kp6k8eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="oth0a1bfn"/><path class="t-a9dubga"/><path class="a98oukb7r"/><path class="zf8ge10as"/><path class="z2kp6k8eh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:angle-left-print" {...props}></Icon>
