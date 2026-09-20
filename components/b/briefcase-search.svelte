<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7oxa7b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7oxa7b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:briefcase-search" {...props}></Icon>
