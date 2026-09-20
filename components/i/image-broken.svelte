<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfv9sopxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yfv9sopxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:image-broken" {...props}></Icon>
