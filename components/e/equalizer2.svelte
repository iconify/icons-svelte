<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_wlcnbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h_wlcnbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:equalizer2" {...props}></Icon>
