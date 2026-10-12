<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo960odbv.css';
import '../../css/t/tcdywobje.css';
import '../../css/y/yyu6w0k1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo960odbv"/><path class="tcdywobje"/><path class="yyu6w0k1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-key-filled" {...props}></Icon>
