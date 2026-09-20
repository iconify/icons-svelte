<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8orw8d-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8orw8d-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:human-male-male-child" {...props}></Icon>
