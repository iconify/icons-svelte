<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhmbtiblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fhmbtiblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dog-wearing-harness" {...props}></Icon>
