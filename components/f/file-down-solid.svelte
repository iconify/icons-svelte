<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llh2aacvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llh2aacvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-down-solid" {...props}></Icon>
