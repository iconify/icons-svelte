<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m249ygu5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m249ygu5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:price-tag" {...props}></Icon>
