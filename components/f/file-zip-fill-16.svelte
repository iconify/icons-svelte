<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_mo4xl-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r_mo4xl-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-zip-fill-16" {...props}></Icon>
