<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq3o7-bqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vq3o7-bqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-text-x" {...props}></Icon>
