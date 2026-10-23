<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqi3bom7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqi3bom7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:clapperboard" {...props}></Icon>
