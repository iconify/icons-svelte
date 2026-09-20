<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhp8hdctn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dhp8hdctn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:apps-16" {...props}></Icon>
