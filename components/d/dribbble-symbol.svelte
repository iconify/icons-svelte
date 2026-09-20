<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz8ds_9ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz8ds_9ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:dribbble-symbol" {...props}></Icon>
