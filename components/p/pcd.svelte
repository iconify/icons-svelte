<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8qez6mxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h8qez6mxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:pcd" {...props}></Icon>
