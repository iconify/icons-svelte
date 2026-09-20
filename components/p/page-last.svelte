<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwx5d7bri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwx5d7bri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:page-last" {...props}></Icon>
