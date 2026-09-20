<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajo6xxbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ajo6xxbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:pin" {...props}></Icon>
