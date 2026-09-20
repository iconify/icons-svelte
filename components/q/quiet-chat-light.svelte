<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_r4442sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o_r4442sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quiet-chat-light" {...props}></Icon>
