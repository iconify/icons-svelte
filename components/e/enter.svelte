<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/mn60u_xaa.css';
import '../../css/s/s72jc8bgn.css';
import '../../css/b/bf7l22bfs.css';
import '../../css/v/vkf35_b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="mn60u_xaa"/><path class="s72jc8bgn"/><path class="bf7l22bfs"/><path class="vkf35_b2l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:enter" {...props}></Icon>
