<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f55313bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f55313bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:receipt-pound-sterling-filled" {...props}></Icon>
