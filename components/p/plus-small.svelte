<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbpw3ccwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":7,"height":16};
const content = `<path class="wbpw3ccwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:plus-small" {...props}></Icon>
