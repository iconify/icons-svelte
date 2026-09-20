<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/diga86qzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="diga86qzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:corner-down-left-fill" {...props}></Icon>
