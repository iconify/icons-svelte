<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djm801buo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djm801buo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:eraser-variant" {...props}></Icon>
