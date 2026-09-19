<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8htw_vfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n8htw_vfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-up-on-square-16-solid" {...props}></Icon>
