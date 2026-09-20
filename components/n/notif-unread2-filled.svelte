<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kd5roj08b.css';
import '../../css/s/s7qf1rb3v.css';
import '../../css/e/e0sr_k7vd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kd5roj08b"/><path clip-rule="evenodd" class="s7qf1rb3v"/><path clip-rule="evenodd" class="e0sr_k7vd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:notif-unread2-filled" {...props}></Icon>
