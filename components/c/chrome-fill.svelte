<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjy1m-bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjy1m-bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chrome-fill" {...props}></Icon>
