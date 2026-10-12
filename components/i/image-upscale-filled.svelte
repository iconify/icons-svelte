<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df_472xle.css';
import '../../css/l/l3uet_-9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="df_472xle"/><path class="l3uet_-9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:image-upscale-filled" {...props}></Icon>
