<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgo93hedx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgo93hedx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:frog" {...props}></Icon>
