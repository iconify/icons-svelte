<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u77n4s6-n.css';
import '../../css/r/rpqxzacuc.css';
import '../../css/e/eeje0kknz.css';
import '../../css/b/bt7scxyyw.css';
import '../../css/u/ui38c_2aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u77n4s6-n wm-k"/><path class="rpqxzacuc wm-a"/><path class="eeje0kknz wm-shadow"/><path class="bt7scxyyw wm-k"/><path class="ui38c_2aq wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:helicopter-engrave" {...props}></Icon>
