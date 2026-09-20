<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvfagilzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":321,"height":294};
const content = `<path class="vvfagilzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:frnkln-technologies" {...props}></Icon>
