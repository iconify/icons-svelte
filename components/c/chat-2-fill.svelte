<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q75iphppk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q75iphppk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-2-fill" {...props}></Icon>
