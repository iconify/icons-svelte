<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg_r_uvrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wg_r_uvrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:download" {...props}></Icon>
