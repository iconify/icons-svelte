<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbc9zibtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nbc9zibtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:link-16" {...props}></Icon>
