<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f48o6q92l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f48o6q92l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:countertop-outline" {...props}></Icon>
