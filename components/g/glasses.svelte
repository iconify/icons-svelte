<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smcp5cl5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smcp5cl5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:glasses" {...props}></Icon>
