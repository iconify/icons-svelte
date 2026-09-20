<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewd3j3yhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewd3j3yhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chat-alert-outline" {...props}></Icon>
