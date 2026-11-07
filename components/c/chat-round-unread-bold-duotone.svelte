<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b133qtshg.css';
import '../../css/o/oq5mzbcjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b133qtshg"/><path class="oq5mzbcjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-unread-bold-duotone" {...props}></Icon>
