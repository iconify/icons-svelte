<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6zcrlbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f6zcrlbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rahoot-dark" {...props}></Icon>
