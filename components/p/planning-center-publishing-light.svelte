<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8wb93x5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p8wb93x5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planning-center-publishing-light" {...props}></Icon>
