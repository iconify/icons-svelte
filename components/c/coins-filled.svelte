<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzgj71bkw.css';
import '../../css/x/xmo5rcozs.css';
import '../../css/w/w_5epib3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzgj71bkw"/><path class="xmo5rcozs"/><path clip-rule="evenodd" class="w_5epib3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:coins-filled" {...props}></Icon>
