<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izndy0u6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izndy0u6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-filter-drama-outline" {...props}></Icon>
