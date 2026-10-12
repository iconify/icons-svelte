<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbehvzotf.css';
import '../../css/w/w-2f6ab8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zbehvzotf"/><path class="w-2f6ab8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:map-pin-off-filled" {...props}></Icon>
