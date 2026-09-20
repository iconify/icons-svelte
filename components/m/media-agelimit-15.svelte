<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvn2jqbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvn2jqbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-agelimit-15" {...props}></Icon>
