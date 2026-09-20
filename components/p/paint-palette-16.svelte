<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idcnk1b5s.css';
import '../../css/x/xqadazbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="idcnk1b5s"/><path clip-rule="evenodd" class="xqadazbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:paint-palette-16" {...props}></Icon>
