<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzpx_acik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uzpx_acik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:face-smile-plus-20-solid" {...props}></Icon>
