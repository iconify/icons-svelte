<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nolwi1iyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nolwi1iyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:cloud-windy-line" {...props}></Icon>
