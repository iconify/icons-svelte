<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5wm4bcad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h5wm4bcad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:chrome-minimize" {...props}></Icon>
