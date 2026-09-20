<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x58xkwtsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x58xkwtsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:briefcase-view-outline" {...props}></Icon>
