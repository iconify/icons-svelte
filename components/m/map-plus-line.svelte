<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzumz54ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzumz54ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-plus-line" {...props}></Icon>
