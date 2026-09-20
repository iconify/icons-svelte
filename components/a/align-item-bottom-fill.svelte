<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fal4x0qhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fal4x0qhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:align-item-bottom-fill" {...props}></Icon>
