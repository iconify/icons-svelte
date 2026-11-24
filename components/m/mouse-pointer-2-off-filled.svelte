<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im7p7qbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="im7p7qbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mouse-pointer-2-off-filled" {...props}></Icon>
