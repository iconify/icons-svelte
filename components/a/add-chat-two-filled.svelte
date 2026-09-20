<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz1l9ignk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tz1l9ignk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:add-chat-two-filled" {...props}></Icon>
