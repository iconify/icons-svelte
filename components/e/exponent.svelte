<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbi8albbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbi8albbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:exponent" {...props}></Icon>
