<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zli93rbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zli93rbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-corner-down-left-down-keyboard-arrow-left-bottom" {...props}></Icon>
