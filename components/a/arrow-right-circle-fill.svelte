<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xds1_qbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xds1_qbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-right-circle-fill" {...props}></Icon>
