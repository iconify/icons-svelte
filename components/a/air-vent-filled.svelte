<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8gghnbuu.css';
import '../../css/x/xhxzdg_-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8gghnbuu"/><path clip-rule="evenodd" class="xhxzdg_-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:air-vent-filled" {...props}></Icon>
