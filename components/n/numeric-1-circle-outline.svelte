<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-w8qbchv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-w8qbchv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-1-circle-outline" {...props}></Icon>
