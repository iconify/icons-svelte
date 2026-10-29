<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jh6lxrb9u.css';
import '../../css/p/p8v2fyboy.css';
import '../../css/t/tzpvtdwuf.css';
import '../../css/x/xdetkr8ld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jh6lxrb9u"/><path class="p8v2fyboy wm-s"/><path class="tzpvtdwuf wm-k"/><path class="wm-s xdetkr8ld"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:phone-incoming-sketch" {...props}></Icon>
