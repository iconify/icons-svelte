<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3a89wb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3a89wb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:resume" {...props}></Icon>
