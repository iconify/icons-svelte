<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em3wahoxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="em3wahoxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-private-line" {...props}></Icon>
