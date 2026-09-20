<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8hz16hbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8hz16hbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:indian-rupee-fill" {...props}></Icon>
