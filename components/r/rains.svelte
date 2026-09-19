<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq733hbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":33,"height":24};
const content = `<path class="vq733hbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:rains" {...props}></Icon>
