<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrizkoc3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrizkoc3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mouse-pointer-2-off-filled" {...props}></Icon>
