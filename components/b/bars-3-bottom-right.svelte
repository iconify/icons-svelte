<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afzffgg-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afzffgg-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:bars-3-bottom-right" {...props}></Icon>
