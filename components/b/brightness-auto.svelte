<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygi1bib1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygi1bib1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:brightness-auto" {...props}></Icon>
