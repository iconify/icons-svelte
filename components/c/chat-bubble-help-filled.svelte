<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz_n9wboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tz_n9wboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chat-bubble-help-filled" {...props}></Icon>
