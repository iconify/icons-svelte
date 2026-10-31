<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz3c6b5lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz3c6b5lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:camera-off-fill-round" {...props}></Icon>
