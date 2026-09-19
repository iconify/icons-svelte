<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmc_7kbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="mmc_7kbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:photo-video" {...props}></Icon>
