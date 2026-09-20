<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xflx9c36z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xflx9c36z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-minus-filled" {...props}></Icon>
