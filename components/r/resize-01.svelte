<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwkn7bcfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwkn7bcfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:resize-01" {...props}></Icon>
