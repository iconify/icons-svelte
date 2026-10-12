<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvql5q15h.css';
import '../../css/v/v8spg71sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvql5q15h"/><path clip-rule="evenodd" class="v8spg71sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:compass-filled" {...props}></Icon>
