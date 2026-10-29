<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dom870b0k.css';
import '../../css/g/g83y6wzjj.css';
import '../../css/h/h7irlhbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dom870b0k wm-k"/><path class="g83y6wzjj wm-k"/><path class="h7irlhbzn wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:laptop-sketch" {...props}></Icon>
