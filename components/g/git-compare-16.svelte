<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha_v22dby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ha_v22dby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-compare-16" {...props}></Icon>
