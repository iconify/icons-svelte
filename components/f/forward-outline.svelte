<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlbtk00yg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlbtk00yg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:forward-outline" {...props}></Icon>
