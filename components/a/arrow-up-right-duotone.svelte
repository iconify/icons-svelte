<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy1u76bbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fy1u76bbj primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-up-right-duotone" {...props}></Icon>
