<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdcn49b2p.css';
import '../../css/z/ze_2m6b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vdcn49b2p"/><path class="ze_2m6b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-directory-symlink-16" {...props}></Icon>
