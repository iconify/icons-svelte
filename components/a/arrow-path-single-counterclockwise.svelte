<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7-336bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7-336bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-path-single-counterclockwise" {...props}></Icon>
