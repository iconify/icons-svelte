<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em2bklzzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="em2bklzzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:microchip-filled" {...props}></Icon>
