<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg2pl9wsr.css';
import '../../css/i/itc5zdbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vg2pl9wsr"/><path class="itc5zdbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-refresh-outline" {...props}></Icon>
