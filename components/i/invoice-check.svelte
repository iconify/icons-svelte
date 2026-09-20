<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yeg7zcc-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yeg7zcc-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-check" {...props}></Icon>
