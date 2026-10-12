<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bapjp_w7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bapjp_w7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:book-x-filled" {...props}></Icon>
