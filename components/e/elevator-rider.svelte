<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qazvk2b5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qazvk2b5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:elevator-rider" {...props}></Icon>
