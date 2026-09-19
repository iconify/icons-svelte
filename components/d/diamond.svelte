<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us80zob-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us80zob-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:diamond" {...props}></Icon>
