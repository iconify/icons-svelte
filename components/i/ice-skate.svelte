<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iaeolubqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iaeolubqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ice-skate" {...props}></Icon>
