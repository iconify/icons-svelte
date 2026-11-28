<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmgi9rbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmgi9rbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:flame" {...props}></Icon>
