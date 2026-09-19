<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc_42ccbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nc_42ccbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloudy" {...props}></Icon>
