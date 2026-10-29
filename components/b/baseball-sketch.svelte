<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/o1dlosizy.css';
import '../../css/o/oadsfbb3w.css';
import '../../css/z/zaj5h4boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="o1dlosizy"/><path class="oadsfbb3w wm-k"/><path class="wm-a zaj5h4boz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:baseball-sketch" {...props}></Icon>
