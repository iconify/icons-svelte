<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r12e13k0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="r12e13k0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:button-previous" {...props}></Icon>
