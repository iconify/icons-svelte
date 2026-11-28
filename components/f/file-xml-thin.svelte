<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2dwiwbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="c2dwiwbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:file-xml-thin" {...props}></Icon>
