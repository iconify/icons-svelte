<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b65qfabyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b65qfabyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:power-box" {...props}></Icon>
