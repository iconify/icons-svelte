<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpojasbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpojasbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-4-boxes-outline" {...props}></Icon>
