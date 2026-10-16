<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz93yvfkk.css';
import '../../css/w/wgr1h7bfy.css';
import '../../css/y/yfoxxnbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lz93yvfkk"/><path class="wgr1h7bfy"/><path class="yfoxxnbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:industrial-boiler-20-bold" {...props}></Icon>
