<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_eief_xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_eief_xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:eye-tick-outline" {...props}></Icon>
