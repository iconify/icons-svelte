<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur95pabmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="ur95pabmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:karaoke-11" {...props}></Icon>
