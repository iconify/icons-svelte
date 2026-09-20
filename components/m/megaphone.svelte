<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zynpte7ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zynpte7ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:megaphone" {...props}></Icon>
