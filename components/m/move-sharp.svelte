<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr-3m1bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cr-3m1bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:move-sharp" {...props}></Icon>
