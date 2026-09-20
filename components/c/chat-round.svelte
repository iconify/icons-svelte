<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnucjk.css';
import '../../css/x/xwdvrd.css';
import '../../css/s/so-from-54.css';
import '../../css/f/fade-to-1.css';
import '../../css/d/d-ssqjbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wnucjk"/><path class="xwdvrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:chat-round" {...props}></Icon>
