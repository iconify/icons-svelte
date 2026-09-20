<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xis_9gy_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xis_9gy_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:movie-line" {...props}></Icon>
