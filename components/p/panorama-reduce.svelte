<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpockd_pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpockd_pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:panorama-reduce" {...props}></Icon>
