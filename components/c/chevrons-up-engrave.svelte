<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f809zybkk.css';
import '../../css/x/x6seubbeo.css';
import '../../css/a/a0b8ycbsz.css';
import '../../css/v/vuv598b9b.css';
import '../../css/w/w7az6qnzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f809zybkk wm-k"/><path class="wm-a x6seubbeo"/><path class="a0b8ycbsz wm-shadow"/><path class="vuv598b9b wm-k"/><path class="w7az6qnzw wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chevrons-up-engrave" {...props}></Icon>
