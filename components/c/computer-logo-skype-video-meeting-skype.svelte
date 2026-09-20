<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a75hd-wnc.css';
import '../../css/y/yu04o0y7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="a75hd-wnc"/><path class="yu04o0y7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-logo-skype-video-meeting-skype" {...props}></Icon>
