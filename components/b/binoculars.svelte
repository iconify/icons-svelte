<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weyi3eb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="weyi3eb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:binoculars" {...props}></Icon>
