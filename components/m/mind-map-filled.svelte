<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5gj8kbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5gj8kbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mind-map-filled" {...props}></Icon>
