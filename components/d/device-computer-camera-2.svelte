<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1y4hnr9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1y4hnr9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-computer-camera-2" {...props}></Icon>
