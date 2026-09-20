<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdp7vcb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tdp7vcb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-notes-dark" {...props}></Icon>
