<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_dt9zbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_dt9zbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:chart-bar-big" {...props}></Icon>
