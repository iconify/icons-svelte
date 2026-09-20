<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y05r1sudp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y05r1sudp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:front-square-outline" {...props}></Icon>
