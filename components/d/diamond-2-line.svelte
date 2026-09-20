<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxjrk3bzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uxjrk3bzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:diamond-2-line" {...props}></Icon>
