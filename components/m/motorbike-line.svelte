<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sof3dcy3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sof3dcy3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:motorbike-line" {...props}></Icon>
