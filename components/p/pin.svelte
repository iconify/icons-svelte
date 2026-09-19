<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhd-yji_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dhd-yji_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:pin" {...props}></Icon>
