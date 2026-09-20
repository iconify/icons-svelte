<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su1vn_25q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="su1vn_25q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:location-down" {...props}></Icon>
