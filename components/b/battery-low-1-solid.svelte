<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4f9vybma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s4f9vybma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:battery-low-1-solid" {...props}></Icon>
