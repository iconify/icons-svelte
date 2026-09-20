<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf59xfbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vf59xfbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lamp-outline" {...props}></Icon>
