<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5ibjvb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t5ibjvb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:fit-to-height-square-solid" {...props}></Icon>
