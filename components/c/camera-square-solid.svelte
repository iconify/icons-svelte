<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwqmksbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fwqmksbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:camera-square-solid" {...props}></Icon>
