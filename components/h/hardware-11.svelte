<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-ansi1om.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="e-ansi1om"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:hardware-11" {...props}></Icon>
