<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obq9c64fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="obq9c64fy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:mic-alt" {...props}></Icon>
