<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9e8i8b7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="j9e8i8b7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:modx" {...props}></Icon>
