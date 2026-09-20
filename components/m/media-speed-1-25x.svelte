<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dghkc8bsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":24};
const content = `<path class="dghkc8bsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-speed-1-25x" {...props}></Icon>
