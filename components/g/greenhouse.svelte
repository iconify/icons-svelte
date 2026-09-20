<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d85fr1bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d85fr1bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:greenhouse" {...props}></Icon>
