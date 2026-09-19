<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdoq8lb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sdoq8lb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:device-camera" {...props}></Icon>
