<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlxk5qbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlxk5qbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:flame-kindling-solid" {...props}></Icon>
