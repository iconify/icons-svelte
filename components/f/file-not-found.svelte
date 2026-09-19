<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypaq_fbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypaq_fbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:file-not-found" {...props}></Icon>
