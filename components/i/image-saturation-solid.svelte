<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgisir4yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fgisir4yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:image-saturation-solid" {...props}></Icon>
