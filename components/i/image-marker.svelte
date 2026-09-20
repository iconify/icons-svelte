<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf1q-jbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sf1q-jbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-marker" {...props}></Icon>
