<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfbmzgbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfbmzgbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-down-round" {...props}></Icon>
