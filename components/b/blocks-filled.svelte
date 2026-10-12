<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys7-5437z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys7-5437z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:blocks-filled" {...props}></Icon>
