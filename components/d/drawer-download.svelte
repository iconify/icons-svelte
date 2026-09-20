<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/f/f1vu3gb0c.css';
import '../../css/h/hbnlznkbn.css';
import '../../css/p/paxlopbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="f1vu3gb0c"/><path class="hbnlznkbn"/><path class="paxlopbiy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:drawer-download" {...props}></Icon>
