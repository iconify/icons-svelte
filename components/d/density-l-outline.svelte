<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr7da0tze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jr7da0tze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:density-l-outline" {...props}></Icon>
