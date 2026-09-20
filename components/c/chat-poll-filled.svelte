<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j224f_kyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j224f_kyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chat-poll-filled" {...props}></Icon>
