<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-uy8yb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-uy8yb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pretzel" {...props}></Icon>
