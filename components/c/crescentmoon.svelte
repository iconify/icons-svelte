<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk2py0bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wk2py0bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:crescentmoon" {...props}></Icon>
