<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hffinzb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hffinzb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:density-s-outline" {...props}></Icon>
