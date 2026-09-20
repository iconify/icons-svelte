<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-6gl2bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-6gl2bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:heart-pause" {...props}></Icon>
