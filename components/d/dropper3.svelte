<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bgl1wz4_k.css';
import '../../css/t/tsh0j704h.css';
import '../../css/j/j5o3tkw7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bgl1wz4_k"/><path class="tsh0j704h"/><path clip-rule="evenodd" class="j5o3tkw7k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:dropper3" {...props}></Icon>
