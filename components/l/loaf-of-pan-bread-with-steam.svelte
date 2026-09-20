<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrhwmpbjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wrhwmpbjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:loaf-of-pan-bread-with-steam" {...props}></Icon>
