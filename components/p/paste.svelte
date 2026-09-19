<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqim73zfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cqim73zfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:paste" {...props}></Icon>
