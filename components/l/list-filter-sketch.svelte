<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v3xxggbuv.css';
import '../../css/f/fngyexhig.css';
import '../../css/d/d6r7_2bbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v3xxggbuv"/><path class="fngyexhig wm-k"/><path class="d6r7_2bbn wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:list-filter-sketch" {...props}></Icon>
