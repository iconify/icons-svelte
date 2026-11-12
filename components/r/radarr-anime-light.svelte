<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc3icy34w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vc3icy34w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:radarr-anime-light" {...props}></Icon>
