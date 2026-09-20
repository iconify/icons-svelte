<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij-3dl-jv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ij-3dl-jv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:blocked-16" {...props}></Icon>
