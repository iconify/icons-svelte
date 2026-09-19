<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m37njk4ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m37njk4ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:haykal" {...props}></Icon>
