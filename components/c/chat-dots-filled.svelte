<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tifla0bgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tifla0bgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-dots-filled" {...props}></Icon>
