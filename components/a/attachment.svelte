<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_ao4bbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d_ao4bbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:attachment" {...props}></Icon>
