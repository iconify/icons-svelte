<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qo3xvyhzr.css';
import '../../css/c/cwjg7g3za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="qo3xvyhzr"/><path clip-rule="evenodd" class="cwjg7g3za"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blister-pills-oval-x42x-outline" {...props}></Icon>
