<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s77lopbsd.css';
import '../../css/a/ajx-gfbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s77lopbsd"/><path class="ajx-gfbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filebrowser-quantum" {...props}></Icon>
