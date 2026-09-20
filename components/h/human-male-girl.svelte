<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrj1l8jwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrj1l8jwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:human-male-girl" {...props}></Icon>
