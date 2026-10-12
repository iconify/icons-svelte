<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bscw5_9wc.css';
import '../../css/l/l2k_u8b-h.css';
import '../../css/y/yyu6w0k1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bscw5_9wc"/><path class="l2k_u8b-h"/><path class="yyu6w0k1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-clock-filled" {...props}></Icon>
