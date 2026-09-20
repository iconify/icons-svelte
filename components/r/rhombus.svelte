<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmaxe4qiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmaxe4qiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rhombus" {...props}></Icon>
