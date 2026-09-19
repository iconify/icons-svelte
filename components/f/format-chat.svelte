<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n--glj5wx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n--glj5wx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:format-chat" {...props}></Icon>
