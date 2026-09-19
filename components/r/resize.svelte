<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0pzumf0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w0pzumf0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:resize" {...props}></Icon>
