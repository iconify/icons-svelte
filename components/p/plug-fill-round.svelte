<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgbug4bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgbug4bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:plug-fill-round" {...props}></Icon>
