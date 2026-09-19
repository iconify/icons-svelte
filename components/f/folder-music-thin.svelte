<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/t/t1jo3sb8s.css';
import '../../css/f/f4rs0cbsv.css';
import '../../css/x/xppvq2ske.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="t1jo3sb8s"/><circle class="f4rs0cbsv"/><path class="xppvq2ske"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:folder-music-thin" {...props}></Icon>
