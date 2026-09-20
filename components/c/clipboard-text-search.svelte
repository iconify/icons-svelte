<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrcby-4rz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrcby-4rz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-text-search" {...props}></Icon>
