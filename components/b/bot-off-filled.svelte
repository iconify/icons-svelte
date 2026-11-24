<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3xx_lb7w.css';
import '../../css/r/rosvxu7bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m3xx_lb7w"/><path class="rosvxu7bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bot-off-filled" {...props}></Icon>
