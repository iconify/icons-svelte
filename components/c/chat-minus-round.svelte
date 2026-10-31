<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmnw-9bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmnw-9bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-minus-round" {...props}></Icon>
