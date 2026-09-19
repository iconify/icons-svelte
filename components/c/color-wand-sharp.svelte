<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evvfitddh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="evvfitddh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:color-wand-sharp" {...props}></Icon>
