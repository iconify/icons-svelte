<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2ffzrbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2ffzrbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:dribbble-logo-bold" {...props}></Icon>
