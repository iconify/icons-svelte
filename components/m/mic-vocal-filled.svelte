<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibo-1vb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibo-1vb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mic-vocal-filled" {...props}></Icon>
