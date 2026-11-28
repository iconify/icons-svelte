<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb3t2lvkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb3t2lvkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:music-play" {...props}></Icon>
