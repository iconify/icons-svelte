<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr2g5kbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr2g5kbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrows-right-down" {...props}></Icon>
