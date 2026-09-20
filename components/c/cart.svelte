<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyodezbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyodezbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cart" {...props}></Icon>
