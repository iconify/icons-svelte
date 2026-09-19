<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4e0i62as.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="v4e0i62as"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-4-bold" {...props}></Icon>
