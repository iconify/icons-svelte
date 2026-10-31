<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guyoekzui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="guyoekzui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-circle-minus-round" {...props}></Icon>
