<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/st4uvqb4z.css';
import '../../css/m/mqb8mfbrm.css';
import '../../css/o/os45fy0ez.css';
import '../../css/z/zsuclwbnx.css';
import '../../css/k/kspoj7vnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="st4uvqb4z"/><path clip-rule="evenodd" class="mqb8mfbrm"/><path clip-rule="evenodd" class="os45fy0ez"/><path class="zsuclwbnx"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:arrow-up-circle-off" {...props}></Icon>
