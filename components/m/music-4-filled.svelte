<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwlk1ebmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lwlk1ebmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:music-4-filled" {...props}></Icon>
