<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3he0ryws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m3he0ryws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:coffee-cup" {...props}></Icon>
