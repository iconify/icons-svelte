<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9anvvtig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="r9anvvtig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-lighting-light-bulb-lighting-light-incandescent-bulb-lights" {...props}></Icon>
