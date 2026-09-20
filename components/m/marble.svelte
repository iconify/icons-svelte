<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_sx0mb9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_sx0mb9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:marble" {...props}></Icon>
