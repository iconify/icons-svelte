<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8pxjbblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="x8pxjbblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-corner-down-right-down-keyboard-arrow-right-bottom" {...props}></Icon>
