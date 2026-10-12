<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8c0nk0pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h8c0nk0pc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:printer-3d-filled" {...props}></Icon>
