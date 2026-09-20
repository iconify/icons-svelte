<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vek31jble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vek31jble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:left-arrow-to-left" {...props}></Icon>
