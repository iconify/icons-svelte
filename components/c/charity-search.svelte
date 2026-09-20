<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9wow2s1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9wow2s1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:charity-search" {...props}></Icon>
