<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_y1_nl1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_y1_nl1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:photo-sensor-3" {...props}></Icon>
