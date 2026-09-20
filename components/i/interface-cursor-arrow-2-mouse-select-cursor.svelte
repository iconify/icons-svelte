<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htuduzbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="htuduzbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-cursor-arrow-2-mouse-select-cursor" {...props}></Icon>
