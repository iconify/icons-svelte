<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yha2iybap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yha2iybap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:poison-outline" {...props}></Icon>
