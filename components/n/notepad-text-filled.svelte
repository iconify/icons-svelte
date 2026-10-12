<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kal9vcqtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kal9vcqtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:notepad-text-filled" {...props}></Icon>
