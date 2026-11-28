<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdlbxko0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdlbxko0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:droplet-heart" {...props}></Icon>
