<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7zzeybvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7zzeybvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:monitor-search" {...props}></Icon>
