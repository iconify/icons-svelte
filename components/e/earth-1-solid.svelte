<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_g12oiot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h_g12oiot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:earth-1-solid" {...props}></Icon>
