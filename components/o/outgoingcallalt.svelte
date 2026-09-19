<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip572gbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ip572gbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:outgoingcallalt" {...props}></Icon>
