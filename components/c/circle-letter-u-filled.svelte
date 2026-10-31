<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbn6nc11z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mbn6nc11z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-letter-u-filled" {...props}></Icon>
