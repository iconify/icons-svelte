<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf5i56b4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xf5i56b4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:add-square-solid" {...props}></Icon>
