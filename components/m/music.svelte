<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f19_pj4xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f19_pj4xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:music" {...props}></Icon>
