<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unhju1fpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="unhju1fpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:3d-rotation" {...props}></Icon>
