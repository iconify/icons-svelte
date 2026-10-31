<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npfmhhbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npfmhhbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-text-fill-round" {...props}></Icon>
