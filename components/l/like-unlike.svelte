<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykmdt0bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ykmdt0bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:like-unlike" {...props}></Icon>
