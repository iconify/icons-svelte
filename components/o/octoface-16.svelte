<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeks_mbgq.css';
import '../../css/m/m7hm-zmpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aeks_mbgq"/><path class="m7hm-zmpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:octoface-16" {...props}></Icon>
