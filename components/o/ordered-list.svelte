<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vub338lzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vub338lzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:ordered-list" {...props}></Icon>
