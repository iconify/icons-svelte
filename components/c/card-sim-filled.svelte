<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkb3d8iqr.css';
import '../../css/v/vxhny_5ct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkb3d8iqr"/><path clip-rule="evenodd" class="vxhny_5ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:card-sim-filled" {...props}></Icon>
