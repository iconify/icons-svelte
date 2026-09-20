<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojm9wsbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":24};
const content = `<path class="ojm9wsbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-speed-2x" {...props}></Icon>
