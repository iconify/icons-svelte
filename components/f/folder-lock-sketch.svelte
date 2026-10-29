<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/txbke2bqd.css';
import '../../css/b/bp_fuo5aq.css';
import '../../css/l/lt_h75dyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="txbke2bqd"/><path class="bp_fuo5aq wm-k"/><path class="lt_h75dyx wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-lock-sketch" {...props}></Icon>
