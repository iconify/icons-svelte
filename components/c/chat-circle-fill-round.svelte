<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2s2su-vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2s2su-vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-circle-fill-round" {...props}></Icon>
