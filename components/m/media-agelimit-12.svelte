<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co215vb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co215vb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-agelimit-12" {...props}></Icon>
