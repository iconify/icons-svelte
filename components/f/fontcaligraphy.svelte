<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf5x249yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sf5x249yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fontcaligraphy" {...props}></Icon>
