<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdmj-0wpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qdmj-0wpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ice-cream-bowl-filled" {...props}></Icon>
