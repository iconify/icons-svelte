<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u31id3bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u31id3bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rhombus" {...props}></Icon>
