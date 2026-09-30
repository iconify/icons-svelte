<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwgw36hjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bwgw36hjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:at-stroke-16" {...props}></Icon>
