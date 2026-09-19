<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbh0l5b0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="xbh0l5b0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:forward" {...props}></Icon>
