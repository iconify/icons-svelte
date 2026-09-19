<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7gaq379y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="j7gaq379y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hand-holding-water" {...props}></Icon>
