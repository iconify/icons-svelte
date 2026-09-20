<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc1iiuhiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xc1iiuhiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:crop-selection-solid" {...props}></Icon>
