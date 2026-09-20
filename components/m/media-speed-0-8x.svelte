<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d457f5bbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":24};
const content = `<path class="d457f5bbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-speed-0-8x" {...props}></Icon>
