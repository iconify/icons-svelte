<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzvuxdb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mzvuxdb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:gender-equality-solid" {...props}></Icon>
