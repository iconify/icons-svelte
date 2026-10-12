<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfj6txbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rfj6txbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:car-filled" {...props}></Icon>
