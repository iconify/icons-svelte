<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu7mpeebk.css';
import '../../css/n/npp4pnb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu7mpeebk"/><path class="npp4pnb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-left-arrow-circle" {...props}></Icon>
