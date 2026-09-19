<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua17pbcnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ua17pbcnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:prime-video-alt" {...props}></Icon>
