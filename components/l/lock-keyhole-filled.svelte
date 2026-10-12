<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzj5p8byf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gzj5p8byf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lock-keyhole-filled" {...props}></Icon>
