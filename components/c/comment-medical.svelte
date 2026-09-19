<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2be4teex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p2be4teex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:comment-medical" {...props}></Icon>
