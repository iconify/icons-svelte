<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky5bn3bkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ky5bn3bkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-hangouts-chat-logo-block" {...props}></Icon>
