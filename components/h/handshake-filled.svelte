<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl98ubb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tl98ubb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:handshake-filled" {...props}></Icon>
