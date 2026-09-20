<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdltf5f5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vdltf5f5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:half-star-1-solid" {...props}></Icon>
