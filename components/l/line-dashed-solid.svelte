<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcfv2bbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcfv2bbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:line-dashed-solid" {...props}></Icon>
