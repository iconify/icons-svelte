<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w63i2sb5q.css';
import '../../css/f/f6sqxlbwl.css';
import '../../css/j/j2p94mlao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w63i2sb5q"/><path class="f6sqxlbwl"/><path class="j2p94mlao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:layers-down-right-filled" {...props}></Icon>
