<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x30gos8ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x30gos8ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:building-search" {...props}></Icon>
