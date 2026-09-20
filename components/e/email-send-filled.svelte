<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgk54msjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wgk54msjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:email-send-filled" {...props}></Icon>
