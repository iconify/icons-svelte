<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji3u0zbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ji3u0zbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:lastfm" {...props}></Icon>
