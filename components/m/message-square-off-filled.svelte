<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw1ncuo8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nw1ncuo8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-square-off-filled" {...props}></Icon>
