<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3rvfy7cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m3rvfy7cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-circle-more-filled" {...props}></Icon>
