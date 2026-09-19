<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itwu3q08m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":408};
const content = `<path class="itwu3q08m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:developer-board" {...props}></Icon>
