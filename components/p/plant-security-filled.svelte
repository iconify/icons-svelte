<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dync3v64e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="dync3v64e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:plant-security-filled" {...props}></Icon>
