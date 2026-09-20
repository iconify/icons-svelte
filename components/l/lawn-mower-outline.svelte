<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_tdshbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_tdshbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lawn-mower-outline" {...props}></Icon>
