<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/o3den9b1v.css';
import '../../css/n/ntbzkabub.css';
import '../../css/x/xxcniyxuf.css';
import '../../css/j/j0bzfeots.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="o3den9b1v wm-k"/><path class="ntbzkabub wm-s"/><path class="wm-k xxcniyxuf"/><path class="j0bzfeots wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:list-plus-sketch" {...props}></Icon>
