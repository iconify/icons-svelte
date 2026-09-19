<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwum6gbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nwum6gbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:delete-filled" {...props}></Icon>
