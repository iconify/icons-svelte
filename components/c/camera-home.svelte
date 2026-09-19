<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5yhzkxgj.css';
import '../../css/c/cag2ndsks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5yhzkxgj"/><path class="cag2ndsks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:camera-home" {...props}></Icon>
