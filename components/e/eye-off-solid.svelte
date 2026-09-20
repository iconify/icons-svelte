<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqb-pdbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aqb-pdbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:eye-off-solid" {...props}></Icon>
