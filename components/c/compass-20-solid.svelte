<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgb4w9bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wgb4w9bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:compass-20-solid" {...props}></Icon>
