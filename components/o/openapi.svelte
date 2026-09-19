<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odrgo8ori.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="odrgo8ori"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:openapi" {...props}></Icon>
