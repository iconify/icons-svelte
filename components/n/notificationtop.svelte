<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-2g_-b-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a-2g_-b-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:notificationtop" {...props}></Icon>
