<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtp_8xwkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gtp_8xwkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:duo-chat-off" {...props}></Icon>
