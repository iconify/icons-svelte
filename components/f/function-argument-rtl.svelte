<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw4_v6bmk.css';
import '../../css/n/ntfhc6rnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pw4_v6bmk"/><path class="ntfhc6rnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:function-argument-rtl" {...props}></Icon>
