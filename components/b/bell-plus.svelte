<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq31b6swd.css';
import '../../css/i/i4yahdcau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq31b6swd"/><path class="i4yahdcau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bell-plus" {...props}></Icon>
