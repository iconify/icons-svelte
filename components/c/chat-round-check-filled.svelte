<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvt3dewrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bvt3dewrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-round-check-filled" {...props}></Icon>
