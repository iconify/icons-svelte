<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we2mvzuyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="we2mvzuyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:debug-check" {...props}></Icon>
