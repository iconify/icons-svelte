<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jy--pbbbh.css';
import '../../css/x/x5caspqqs.css';
import '../../css/o/o4j8kacgj.css';
import '../../css/z/zvmrzybbz.css';
import '../../css/z/zzq0oubsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jy--pbbbh"/><path class="wm-a x5caspqqs"/><path class="o4j8kacgj wm-k"/><path class="wm-a zvmrzybbz"/><path class="wm-s zzq0oubsm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-alien-sketch" {...props}></Icon>
