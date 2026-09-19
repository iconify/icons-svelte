<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_dkhvbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w_dkhvbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:cdn" {...props}></Icon>
