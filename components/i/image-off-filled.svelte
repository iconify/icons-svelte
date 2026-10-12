<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6fz4cbaf.css';
import '../../css/w/wvjpim6nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r6fz4cbaf"/><path class="wvjpim6nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:image-off-filled" {...props}></Icon>
