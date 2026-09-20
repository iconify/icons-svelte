<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8j3nwbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j8j3nwbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:package-16" {...props}></Icon>
