<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nszo3v0eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nszo3v0eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:circle-expand" {...props}></Icon>
