<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2p0rybqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2p0rybqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-sync-outline" {...props}></Icon>
