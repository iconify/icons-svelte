<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysj6xpb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ysj6xpb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cooling" {...props}></Icon>
