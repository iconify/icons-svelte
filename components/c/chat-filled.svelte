<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3gdeyo5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3gdeyo5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chat-filled" {...props}></Icon>
