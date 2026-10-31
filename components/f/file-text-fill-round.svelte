<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id7o3weik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="id7o3weik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-text-fill-round" {...props}></Icon>
