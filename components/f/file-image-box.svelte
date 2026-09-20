<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji752cxbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ji752cxbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-image-box" {...props}></Icon>
