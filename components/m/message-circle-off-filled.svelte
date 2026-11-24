<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-t87l60n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-t87l60n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-circle-off-filled" {...props}></Icon>
