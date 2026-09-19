<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lio3y5lbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lio3y5lbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:ev-station-fill" {...props}></Icon>
