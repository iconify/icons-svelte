<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upjz_j38p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="upjz_j38p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:libreoffice" {...props}></Icon>
