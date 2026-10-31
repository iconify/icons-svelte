<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz6l8ac5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rz6l8ac5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:play-pause-fill-round" {...props}></Icon>
