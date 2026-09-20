<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9czsj7qk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="n9czsj7qk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:media-pause" {...props}></Icon>
