<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e60mj5bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e60mj5bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:file-explorer-light" {...props}></Icon>
