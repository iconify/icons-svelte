<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wououk7rn.css';
import '../../css/x/xg3rfmbqu.css';
import '../../css/t/t1n7njqvt.css';
import '../../css/w/w2jcjnb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wououk7rn"/><path class="wm-a xg3rfmbqu"/><path class="t1n7njqvt wm-k"/><path class="w2jcjnb0u wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:layers-sketch" {...props}></Icon>
