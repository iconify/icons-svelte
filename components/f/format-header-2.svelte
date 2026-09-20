<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx3slkn2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cx3slkn2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-header-2" {...props}></Icon>
