<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt1hwd0eh.css';
import '../../css/l/l2zpy5eyh.css';
import '../../css/y/yyu6w0k1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt1hwd0eh"/><path class="l2zpy5eyh"/><path class="yyu6w0k1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-music-filled" {...props}></Icon>
