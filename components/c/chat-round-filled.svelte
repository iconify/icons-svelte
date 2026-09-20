<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxi53eduq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxi53eduq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-round-filled" {...props}></Icon>
