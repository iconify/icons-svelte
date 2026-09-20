<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdcorkbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qdcorkbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-and-locked-lock-with-keyhole" {...props}></Icon>
