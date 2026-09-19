<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd3uh_z7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hd3uh_z7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-up-box-stroke-16" {...props}></Icon>
