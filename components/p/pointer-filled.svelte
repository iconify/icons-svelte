<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qal3xabty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qal3xabty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pointer-filled" {...props}></Icon>
