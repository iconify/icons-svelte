<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nvx55zk_o.css';
import '../../css/b/by10jt0fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="nvx55zk_o"/><path class="by10jt0fw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-earmark-image" {...props}></Icon>
