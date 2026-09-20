<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td9g1kbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="td9g1kbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:octoface" {...props}></Icon>
