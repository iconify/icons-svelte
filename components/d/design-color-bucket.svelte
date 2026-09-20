<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_4157bgu.css';
import '../../css/f/frw4m7ekt.css';
import '../../css/e/ehesr7bob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r_4157bgu"/><path class="frw4m7ekt"/><path class="ehesr7bob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:design-color-bucket" {...props}></Icon>
