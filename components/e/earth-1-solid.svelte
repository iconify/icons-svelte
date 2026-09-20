<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiy_nybza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fiy_nybza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:earth-1-solid" {...props}></Icon>
