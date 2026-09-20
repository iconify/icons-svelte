<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7fmnlb4r.css';
import '../../css/c/cuabdubep.css';
import '../../css/g/guewfbcxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="cuabdubep"/><path class="guewfbcxi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:eye-line" {...props}></Icon>
