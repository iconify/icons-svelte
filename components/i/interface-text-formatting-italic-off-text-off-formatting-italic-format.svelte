<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsthl7beb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rsthl7beb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-text-formatting-italic-off-text-off-formatting-italic-format" {...props}></Icon>
