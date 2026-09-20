<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlze138cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlze138cm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:npm-variant-outline" {...props}></Icon>
