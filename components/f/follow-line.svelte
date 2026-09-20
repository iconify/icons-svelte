<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf3u6-btt.css';
import '../../css/d/dcscq4zhc.css';
import '../../css/u/umtu9dbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wf3u6-btt"/><path class="dcscq4zhc"/><path class="umtu9dbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:follow-line" {...props}></Icon>
