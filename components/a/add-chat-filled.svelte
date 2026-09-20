<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yroy_z5el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yroy_z5el"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:add-chat-filled" {...props}></Icon>
