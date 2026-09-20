<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-4zjnb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-4zjnb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chevron-left-first" {...props}></Icon>
