<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5et0bbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5et0bbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:info-circle" {...props}></Icon>
