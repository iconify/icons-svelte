<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbdr8ifnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nbdr8ifnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:chat-bubble-disable-oval-solid" {...props}></Icon>
