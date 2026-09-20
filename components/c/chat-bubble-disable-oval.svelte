<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrwtoskyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrwtoskyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:chat-bubble-disable-oval" {...props}></Icon>
