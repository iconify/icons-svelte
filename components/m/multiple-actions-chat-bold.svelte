<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0yqaacfm.css';
import '../../css/g/g4ri23blu.css';
import '../../css/h/hovqi_wid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0yqaacfm"/><path class="g4ri23blu"/><path class="hovqi_wid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:multiple-actions-chat-bold" {...props}></Icon>
