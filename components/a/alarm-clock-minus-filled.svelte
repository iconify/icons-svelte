<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkrexjm2i.css';
import '../../css/t/tl712yvzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tkrexjm2i"/><path class="tl712yvzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:alarm-clock-minus-filled" {...props}></Icon>
