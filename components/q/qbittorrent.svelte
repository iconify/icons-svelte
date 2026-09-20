<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz_jw2b8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rz_jw2b8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:qbittorrent" {...props}></Icon>
