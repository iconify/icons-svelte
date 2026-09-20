<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr96d1e5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sr96d1e5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clock-off" {...props}></Icon>
