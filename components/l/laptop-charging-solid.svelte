<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt639tbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zt639tbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:laptop-charging-solid" {...props}></Icon>
