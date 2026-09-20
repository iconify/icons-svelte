<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3oy44bed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3oy44bed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:navigation-menu-1" {...props}></Icon>
