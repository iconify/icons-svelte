<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdkktcctn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdkktcctn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:qi" {...props}></Icon>
