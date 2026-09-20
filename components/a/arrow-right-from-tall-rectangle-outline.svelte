<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrktzrbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yrktzrbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-right-from-tall-rectangle-outline" {...props}></Icon>
