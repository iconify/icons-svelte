<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/l/lggenxbcp.css';
import '../../css/w/welf67bgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="lggenxbcp"/><path class="welf67bgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bax" {...props}></Icon>
