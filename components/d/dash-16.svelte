<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhc7zy51m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xhc7zy51m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:dash-16" {...props}></Icon>
