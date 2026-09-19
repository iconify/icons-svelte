<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkyf5esrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":24};
const content = `<path class="bkyf5esrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:mars-stroke-v" {...props}></Icon>
