<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rab22r5bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rab22r5bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:bone-flat" {...props}></Icon>
