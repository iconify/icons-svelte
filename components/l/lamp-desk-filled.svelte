<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7tvawbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b7tvawbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lamp-desk-filled" {...props}></Icon>
