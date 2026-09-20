<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6rx894qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n6rx894qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:brick-wall" {...props}></Icon>
