<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzb7ntb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xzb7ntb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:duo-chat-new" {...props}></Icon>
