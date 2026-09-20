<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4ji765zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="x4ji765zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:link-external" {...props}></Icon>
