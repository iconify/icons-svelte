<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjydd_bfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tjydd_bfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-chevrons-up-filled" {...props}></Icon>
