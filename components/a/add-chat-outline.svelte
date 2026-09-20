<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l957qrbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l957qrbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:add-chat-outline" {...props}></Icon>
