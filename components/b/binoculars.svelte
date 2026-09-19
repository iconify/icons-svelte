<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teoaifbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="teoaifbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:binoculars" {...props}></Icon>
