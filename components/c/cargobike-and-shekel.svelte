<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jze4w4b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jze4w4b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cargobike-and-shekel" {...props}></Icon>
