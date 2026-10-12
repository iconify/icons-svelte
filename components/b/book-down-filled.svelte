<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax_u4j-wl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ax_u4j-wl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:book-down-filled" {...props}></Icon>
