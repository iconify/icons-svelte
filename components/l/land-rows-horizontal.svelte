<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-z8-fb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-z8-fb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:land-rows-horizontal" {...props}></Icon>
