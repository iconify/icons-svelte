<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/up7p63bem.css';
import '../../css/c/cwjg7g3za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="up7p63bem"/><path clip-rule="evenodd" class="cwjg7g3za"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blister-pills-oval-x12x-outline" {...props}></Icon>
