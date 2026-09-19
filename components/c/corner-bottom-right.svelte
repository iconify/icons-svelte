<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0y7sbc5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0y7sbc5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:corner-bottom-right" {...props}></Icon>
