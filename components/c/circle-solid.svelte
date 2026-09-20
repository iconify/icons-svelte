<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnpz_eeaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wnpz_eeaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:circle-solid" {...props}></Icon>
