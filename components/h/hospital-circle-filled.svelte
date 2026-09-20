<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqi5v1bhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqi5v1bhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hospital-circle-filled" {...props}></Icon>
