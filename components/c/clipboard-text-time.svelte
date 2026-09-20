<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zodeasbjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zodeasbjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-text-time" {...props}></Icon>
