<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu90i71ig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu90i71ig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chili-medium-outline" {...props}></Icon>
