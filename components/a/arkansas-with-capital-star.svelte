<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv2hpe3im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wv2hpe3im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arkansas-with-capital-star" {...props}></Icon>
