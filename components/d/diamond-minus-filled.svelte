<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeb15m5ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jeb15m5ay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:diamond-minus-filled" {...props}></Icon>
