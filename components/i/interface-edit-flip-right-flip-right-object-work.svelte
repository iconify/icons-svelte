<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wacgaabsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wacgaabsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-edit-flip-right-flip-right-object-work" {...props}></Icon>
