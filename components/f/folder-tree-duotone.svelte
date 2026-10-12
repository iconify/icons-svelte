<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/emwx-3k0l.css';
import '../../css/w/wqx342l3h.css';
import '../../css/j/j1pmrcoqo.css';
import '../../css/r/r1x6x451g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="emwx-3k0l"/><path class="wqx342l3h"/><path class="j1pmrcoqo"/><path class="r1x6x451g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-tree-duotone" {...props}></Icon>
