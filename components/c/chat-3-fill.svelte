<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk7l2_b1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk7l2_b1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chat-3-fill" {...props}></Icon>
