<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/p/pr4f-9s_n.css';
import '../../css/r/ra5ekzk-k.css';
import '../../css/d/dkikyne8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="pr4f-9s_n"/><path class="ra5ekzk-k"/><path class="dkikyne8i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:new-api" {...props}></Icon>
