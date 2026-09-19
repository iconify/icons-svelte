<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psf_9jbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="psf_9jbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hippo" {...props}></Icon>
