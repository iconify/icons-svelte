<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsn7_zb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rsn7_zb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:center-horizontally-outline" {...props}></Icon>
