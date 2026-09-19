<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1_gjbm1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1_gjbm1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:guest-height-limit" {...props}></Icon>
