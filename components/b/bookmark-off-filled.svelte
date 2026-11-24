<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4tca7g_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4tca7g_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bookmark-off-filled" {...props}></Icon>
