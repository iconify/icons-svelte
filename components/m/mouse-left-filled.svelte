<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf9g28u7s.css';
import '../../css/t/tbc_z2b1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sf9g28u7s"/><path class="tbc_z2b1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mouse-left-filled" {...props}></Icon>
