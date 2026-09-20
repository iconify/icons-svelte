<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7snm4f3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r7snm4f3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:image-location-solid" {...props}></Icon>
