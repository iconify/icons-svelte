<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx7r32bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sx7r32bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-arrow-round-back" {...props}></Icon>
