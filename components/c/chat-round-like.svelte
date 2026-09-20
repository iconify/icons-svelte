<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v26cdt2bo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v26cdt2bo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-round-like" {...props}></Icon>
