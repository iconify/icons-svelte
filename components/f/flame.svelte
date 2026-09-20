<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry9lquaxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry9lquaxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:flame" {...props}></Icon>
