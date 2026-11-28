<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgd4_bb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgd4_bb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-big-down-solid" {...props}></Icon>
