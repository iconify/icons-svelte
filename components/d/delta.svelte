<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0wndub2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0wndub2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:delta" {...props}></Icon>
