<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n19k09bae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n19k09bae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bubble-chat-add" {...props}></Icon>
