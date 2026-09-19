<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgb91bumo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgb91bumo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-to-top-stroke" {...props}></Icon>
