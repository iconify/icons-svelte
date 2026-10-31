<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5eak3k2p.css';
import '../../css/w/wkp122bpd.css';
import '../../css/k/k5sbk1u4q.css';
import '../../css/p/pxqahlbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="l5eak3k2p"><circle class="wkp122bpd wm-shadow"/><circle class="k5sbk1u4q"/><circle class="pxqahlbbz wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:circle-dot" {...props}></Icon>
