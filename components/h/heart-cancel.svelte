<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w--d-vlxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w--d-vlxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:heart-cancel" {...props}></Icon>
