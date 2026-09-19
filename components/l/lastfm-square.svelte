<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr0w__b2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="rr0w__b2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:lastfm-square" {...props}></Icon>
