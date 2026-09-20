<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-pu6wzxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i-pu6wzxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:home-fill-16" {...props}></Icon>
