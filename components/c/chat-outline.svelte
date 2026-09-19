<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf6woy2-u.css';
import '../../css/m/mr124pbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sf6woy2-u"/><path clip-rule="evenodd" class="mr124pbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:chat-outline" {...props}></Icon>
