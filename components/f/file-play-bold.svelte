<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmcbpk9ji.css';
import '../../css/x/xxwz847qq.css';
import '../../css/w/wm3j448rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmcbpk9ji"/><path clip-rule="evenodd" class="xxwz847qq"/><path class="wm3j448rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-play-bold" {...props}></Icon>
