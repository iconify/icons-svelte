<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k47fgybkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k47fgybkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nyt-tiles-light" {...props}></Icon>
