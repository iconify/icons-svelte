<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj_sf5b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jj_sf5b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:font-family" {...props}></Icon>
