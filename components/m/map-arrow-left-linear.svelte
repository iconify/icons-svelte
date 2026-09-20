<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1723bvbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1723bvbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-arrow-left-linear" {...props}></Icon>
