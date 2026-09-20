<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plg9hea-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="plg9hea-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:chat-bubble" {...props}></Icon>
