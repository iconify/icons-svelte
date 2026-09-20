<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xesh5zbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xesh5zbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:headphones" {...props}></Icon>
