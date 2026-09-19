<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzw2gxtkm.css';
import '../../css/f/f6sqxlbwl.css';
import '../../css/j/j2p94mlao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzw2gxtkm"/><path class="f6sqxlbwl"/><path class="j2p94mlao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:layers-down-right" {...props}></Icon>
