<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn3b59bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn3b59bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:mushroom-check" {...props}></Icon>
