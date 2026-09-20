<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4s2hkl6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4s2hkl6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:map-search" {...props}></Icon>
