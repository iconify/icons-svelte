<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llc-1mbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="llc-1mbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:lightning" {...props}></Icon>
