<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2l0cwc7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":448};
const content = `<path class="p2l0cwc7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:align-justified" {...props}></Icon>
