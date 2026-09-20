<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5dp0acml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z5dp0acml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pangolin" {...props}></Icon>
