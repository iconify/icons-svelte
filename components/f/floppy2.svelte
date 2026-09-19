<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozy7hsv8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ozy7hsv8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:floppy2" {...props}></Icon>
