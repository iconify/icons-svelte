<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy6a_fh8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dy6a_fh8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:gltf" {...props}></Icon>
