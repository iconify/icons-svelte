<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0gabfc7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0gabfc7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:corner-down-left" {...props}></Icon>
