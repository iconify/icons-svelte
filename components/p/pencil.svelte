<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylq7u89oc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ylq7u89oc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:pencil" {...props}></Icon>
