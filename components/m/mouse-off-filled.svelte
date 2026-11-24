<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu04c6ibz.css';
import '../../css/l/ly-oin5oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eu04c6ibz"/><path clip-rule="evenodd" class="ly-oin5oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mouse-off-filled" {...props}></Icon>
