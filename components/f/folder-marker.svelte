<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fidx61bnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fidx61bnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-marker" {...props}></Icon>
