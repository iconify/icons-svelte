<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxmijccds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxmijccds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:grid-3x3-filled" {...props}></Icon>
