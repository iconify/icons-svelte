<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd1-qvbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd1-qvbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:license" {...props}></Icon>
