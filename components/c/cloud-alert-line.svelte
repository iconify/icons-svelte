<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuy8ujbot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wuy8ujbot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cloud-alert-line" {...props}></Icon>
