<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l8tv5d0oq.css';
import '../../css/o/o3z9n3s0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="l8tv5d0oq"/><path clip-rule="evenodd" class="o3z9n3s0x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:layout-menubar" {...props}></Icon>
