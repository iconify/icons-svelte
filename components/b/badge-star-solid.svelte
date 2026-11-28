<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfgpk5x8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfgpk5x8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-star-solid" {...props}></Icon>
