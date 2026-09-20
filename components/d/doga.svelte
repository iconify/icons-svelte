<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy3vbebii.css';
import '../../css/p/pshtltbvx.css';
import '../../css/y/yax9-yihq.css';
import '../../css/u/u4n-q8ifu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iy3vbebii"/><path class="pshtltbvx"/><path clip-rule="evenodd" class="yax9-yihq"/><path class="u4n-q8ifu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:doga" {...props}></Icon>
