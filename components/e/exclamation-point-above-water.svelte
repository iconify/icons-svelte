<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5p60rbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g5p60rbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:exclamation-point-above-water" {...props}></Icon>
