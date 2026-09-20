<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccfbopbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccfbopbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:location-dollar" {...props}></Icon>
