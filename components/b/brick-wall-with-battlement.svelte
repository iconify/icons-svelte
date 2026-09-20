<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0j8rpbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m0j8rpbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:brick-wall-with-battlement" {...props}></Icon>
