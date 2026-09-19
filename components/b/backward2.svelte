<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbpx2jbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mbpx2jbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:backward2" {...props}></Icon>
