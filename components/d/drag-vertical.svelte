<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydn3x3baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydn3x3baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:drag-vertical" {...props}></Icon>
