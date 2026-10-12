<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9xuyyhvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9xuyyhvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:flame-kindling-filled" {...props}></Icon>
