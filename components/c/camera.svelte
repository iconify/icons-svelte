<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da1dk-x7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="da1dk-x7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:camera" {...props}></Icon>
