<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2gy-yl-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2gy-yl-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-vertical-center-bold" {...props}></Icon>
