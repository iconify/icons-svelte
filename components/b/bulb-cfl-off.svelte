<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mabpczbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mabpczbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bulb-cfl-off" {...props}></Icon>
