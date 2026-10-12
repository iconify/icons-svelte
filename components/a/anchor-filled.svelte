<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk2_ziukt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xk2_ziukt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:anchor-filled" {...props}></Icon>
