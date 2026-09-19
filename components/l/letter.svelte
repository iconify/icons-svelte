<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/vu7wtwbow.css';
import '../../css/q/qdyhayb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="vu7wtwbow"/><path class="qdyhayb_x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:letter" {...props}></Icon>
