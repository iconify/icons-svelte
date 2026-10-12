<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgehs5t-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgehs5t-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lamp-wall-down-filled" {...props}></Icon>
