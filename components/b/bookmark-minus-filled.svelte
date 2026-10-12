<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws8crccai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ws8crccai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bookmark-minus-filled" {...props}></Icon>
