<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv6pukbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dv6pukbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hexagon-close-round" {...props}></Icon>
